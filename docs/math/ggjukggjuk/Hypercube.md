---
title : 하이퍼 큐브
layout : default
parent : 끄적이는 것
grand_parent: 수학📏
nav_order : 1
---

# Hypercube

## Hypercube 관찰

엄밀한 증명 X, 직관적인 부분으로 관찰.

0차원 : 점(아무)

1차원 : 선(아무)

2차원 : 정사각형

3차원 : 정육면체

직관적으로 이해하기 위해 n개의 orthonomal vector로 구성된 h-cube를 생각하였다.

## I. Vertex

0d : 1

1d : 2

2d : 4

3d : 8

딱봐도 $2^n$개 같다.

$n$개의 단위벡터로 구성되었기 때문에 각각의 벡터가 있을 때, 없을 때를 곱해주면 $2^n$일 것이다.

## II. Face

Edge를 안한 이유는 굳이 하고 싶지 않기 때문이다.

0d : 0

1d : 0

2d : 1

3d : 6

직관적으로 떠올리기 어려울 수 있지만 면을 구성하는 것은 두 개의 단위벡터라고 생각하였고, 나머지 벡터들은 껐다 켰다만 구해주면 되기에

${n \choose 2}2^{n-2}$일 것이다. 물론 아닐수도 있다.

## III. $d_2$-cube in $d_1$-cube

사실

Vertex : 0d-cube

Edge : 1d-cube

Face : 2d-cube

...등등

라고 볼 수 있다.

즉 개수의 일반화를 시켜보자면 II에서 했던 것처럼 $d_2$-cube를 구성하는 벡터는 $d_2$개이다.

$d_1$-cube에서 $d_2$개를 고른 후 남은 벡터의 개수는 $d_1-d_2$개일 것이니 개수는 ${d_1 \choose d_2}2^{d1-d2}$라고 떠올릴 수 있다.

## IV. 오일러 지표

 4차 이상은 안되는 듯.