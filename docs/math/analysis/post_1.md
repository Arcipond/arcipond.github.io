---
title : Measure Theory 1
layout : default
parent : 해석학
grand_parent: 수학📏
nav_order : 1
---
# Measure Theory

## Topology

$\tau$가 집합 $X$의 부분집합들의 모임일 때, 다음 세 가지 성질을 만족하면 $\tau$는 $X$의 위상이라고 한다. ($V \in \tau$)

> &emsp;(i) $\empty \in \tau$ 이며, $X \in \tau$<br>&emsp;(ii) $\bigcap_{i=1}^n V_n \in \tau$<br>&emsp;(iii) $\{V_\alpha\}$가 $\tau$의 원소들의 모임이라면, $\bigcup_\alpha V_\alpha \in \tau$

\
$(X, \tau)$ 또는 줄여서 $X$는 위상 공간이라 하고, $\tau$의 원소들은 $X$의 열린 집합이라고 한다.

$X$와 $Y$가 위상공간이고, $f$가 $X$에서 $Y$로의 사상일때, $Y$의 모든 열린집합 $V$에 대해 $f^{-1}(V)$가 $X$의 열린 집합이라면, $f$는 연속이라고 한다.

## $\sigma$-algebra

$\mathfrak M$이 집합 $X$의 부분집합들의 모임일 때, 다음 세 가지 성질을 만족하면 $\mathfrak M$는 $X$의 $\sigma$-대수라고 한다. ($A \in \mathfrak M$)

> &emsp;(i) $X \in \mathfrak M$<br>&emsp;(ii) $A \in \mathfrak M, A^c \in \mathfrak M$<br>&emsp;(iii) $\bigcap_{n=1}^\infty A_n \in \mathfrak M$

\
$(X, \mathfrak M)$ 또는 줄여서 $X$는 가측 공간이라 하고, $\mathfrak M$의 원소들은 $X$의 가측 집합이라고 한다.

$X$가 가측공간, $Y$가 위상공간이고, $f$가 $X$에서 $Y$로의 사상일때, $Y$의 모든 열린집합 $V$에 대해 $f^{-1}(V)$가 $X$의 가측 집합이라면, $f$는 가측이라고 한다.
- - -
reference : real and complex analysis