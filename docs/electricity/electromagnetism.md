---
layout: default
title: 전기자기학
parent: Electricity
nav_order: 3
use_math: true
---

# 전기자기학
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## 상수

---

### 전자

<br>

전자의 질량 : $9.1093826 \times 10^{-31}$ [kg]<br><br>
전자 1개의 전하량 : $1.6021773349 \times 10^{-19} [C]$<br><br>
1쿨롱에 해당하는 전자 갯수 :$\frac{1}{1.6021773349 \times 10^{-19}} = {6.24150962915265 × 10^{18}} [개]$

---

### 전계 자계

<br>

진공의 유전률 : $\epsilon_0 = 8.8541878176 \times 10^{−12} [F/m]$ (매질이 저장할 수 있는 전하량)<br><br>
진공의 투자율 : $\mu_0 = 4\pi \times 10^{-7} [H/m]$ (매질이 자화되는 정도)<br><br>
빛의 속도 : $C = 3 \times 10^8 [m/s]$<br><br>
유전률, 투자율, 광속의 관계 : $\epsilon_0 = \frac{1}{C^2\times\mu_0}$<br><br>
쿨롱 상수 : $k = \frac{1}{4\pi\epsilon_0} = 8.99 \times 10^9 [N \cdot m^2 / C^2]$<br><br>
전기력선의 갯수(가우스 법칙 $\in$ 맥스웰 방정식) : $N = \frac{Q}{\epsilon_0} = \frac{1}{8.8541878176 \times 10^{−12}} = 1.13 \times 10^{11} [개]$

---

### 에너지

<br>

$1 [kg] = 9.8 [N]$<br><br>
$1 [N \cdot m] = 1 [J] = 1 [W \cdot s] = 0.239 [cal]$<br><br>
$1 [kWh] = 860 [kcal]$

---

## 맥스웰 방정식

| 이름                     | 미분형                                                | 적분형 | 의미                                          |
|:-------------------------|:-----------------------------------------------------|:-------|:---------------------------------------------|
| 가우스 법칙              | $\nabla \cdot D = \rho$                               |        | 전하는 전기장을 만듬(전속밀도의 발산은 전하밀도) |
| 가우스 자기 법칙         | $\nabla \cdot B = 0$                                   |        | 자기홀극자는 존재하지 않음(자기장의 발산은 0)   |
| 패러데이 전자기 유도 법칙 | $\nabla \times E = - \frac{\partial B}{\partial t}$   |        | 자기장이 변하면 전기장이 생성됨(rot E)          |
| 앙페르-맥스웰 회로 법칙   | $\nabla \times H = J + \frac{\partial D}{\partial t}$ |        | 전기장이 변하면 자기장이 생성됨(rot H)         |