# 文小剛量子多體物理解答
## Xiao Gang Wen QMB Exercises Solutions

> kk 22 07 28

### 動機 Motivation

>一直沒看到有人寫解答本。
I didn't see any solution manual released online.




##  [課本 The Text Book](http://materias.df.uba.ar/cuanticaa2018c2/files/2012/07/wen_quantum_field_theory_of_many-body_systems_from_the_origin_of_sound_to_an_origin_of_light_and_electrons.pdf)

---
## Ch2 單粒子系統與路徑積分 Single Particle System and Path Integral
---
### 2.1.1 討論並說明量子諧振子的頻率空間傳播子的極點結構。 Discuss and explain the pole structure of the freqeuncy-domain propagator of a quantum oscillator.
---
#### Answer
I only show the case $m=\omega=x_b=1,x_a=0$,

$G(x_b,t,x_a,0)=G(1,t,0,0) = -i {\frac{1}{2\pi\sin(t)}}^{1/2}e^{\frac{i}{2\pi\sin t}\;\cos t}$

$FT(G)=\pi\delta(\omega)+\sqrt\pi\delta(\omega)+FT({\frac{1}{\sin t}}^{1/2})+FT(e^{{\frac{i}{2\pi\sin t}}})+FT(e^{\cos t})$
where $FT:$ Fourier transform.

Hence G at least has one pole at $\omega=0$

---
#### 參考資料 Reference
[Fourier table wiki](https://en.wikipedia.org/wiki/Fourier_transform)
[Discussion about pole(s) of a propagator](https://physics.stackexchange.com/questions/554243/physical-interpretation-of-propagator-pole)
[Källén–Lehmann_spectral_representation](https://en.wikipedia.org/wiki/K%C3%A4ll%C3%A9n%E2%80%93Lehmann_spectral_representation)

---
#### 工具 Tools

[Fourier Transform Calculator (Wolfram Alpha)](https://www.wolframalpha.com/input?i=Fourier+transform+calculator&assumption=%7B%22F%22%2C+%22FourierTransformCalculator%22%2C+%22transformfunction%22%7D+-%3E%22%281%2F%282*pi*sin%28t%29%29%5E%281%2F2%29%22&assumption=%7B%22F%22%2C+%22FourierTransformCalculator%22%2C+%22variable1%22%7D+-%3E%22t%22&assumption=%7B%22F%22%2C+%22FourierTransformCalculator%22%2C+%22variable2%22%7D+-%3E%22w%22)
[Sympy](https://www.sympy.org/en/index.html)

---

### 2.1.2 

See Sakurai's QM text book (2nd ver.),section 2.7.
Hint: $[x_i,x_j]$=0, so you can easily generalized from the 1D version.

---

