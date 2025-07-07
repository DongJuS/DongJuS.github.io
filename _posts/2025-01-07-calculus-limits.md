---
layout: post
title: "미적분학 기초: 극한의 개념"
date: 2025-01-07 15:00:00 +0900
categories: [mathematics, calculus]
math: true
---

# 극한의 정의

함수의 극한은 미적분학의 가장 기본적인 개념입니다.

## 직관적 이해

함수 $f(x) = x^2$를 생각해봅시다. $x$가 2에 가까워질 때 $f(x)$는 4에 가까워집니다:

$$\lim_{x \to 2} x^2 = 4$$

## 엄밀한 정의 (epsilon-delta)

함수 $f(x)$가 $x = a$에서 극한값 $L$을 가진다는 것은:

임의의 $\epsilon > 0$에 대하여 적당한 $\delta > 0$가 존재하여

$$0 < |x - a| < \delta \implies |f(x) - L| < \epsilon$$

## 연습 문제

다음 극한을 구해보세요:

1. $\lim_{x \to 3} (2x + 1)$
2. $\lim_{x \to 0} \frac{\sin x}{x}$

### 해답

1. $\lim_{x \to 3} (2x + 1) = 2(3) + 1 = 7$

2. $\lim_{x \to 0} \frac{\sin x}{x} = 1$ (이는 유명한 극한입니다)

이 극한은 다음과 같이 증명할 수 있습니다:

$$\cos x < \frac{\sin x}{x} < 1$$

사잇값 정리에 의해 결과를 얻습니다.