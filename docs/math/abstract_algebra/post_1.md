---
title: Monoid와 Group
layout: default
parent: 대수
grand_parent: 수학📏
nav_order: 1
---
# Monoid와 Group

monoid와 group(군)은 $S \times S \to S$로 정의되는 mapping(law of composition)과 집합으로 정의되는 기본 구조이다. 이 mapping은 맥락에 따라 $\cdot$ (product) 혹은 $+$ (sum)로 나타낸다.

## Monoid
Monoid는 law of composition이 다음이 성립하는 집합 $G$를 말한다.

- associative (결합법칙)
	모든 $x,y,z \in G$에 대해 $(xy)z = x(yz)$
- having a unit element (항등원의 존재)
	모든 $x \in G$에 대해 $ex = x = xe$를 만족하는 $e \in G$ (unit element) 존재

정의가 시사함에 따라 $e$의 좌우대칭성을 확인해야 한다. (기본적으로 law of composition이 교환법칙을 가정하지 않는다) 또한 $e$가 유일함을 확인할 수 있다.

$\mathbb{R}$과 $\times$가 unit element를 1로 갖는 monoid라는 것을 알 수 있다.



## Group
Group은 모든 원소의 역원이 존재하는 monoid이며, 따라서 law of composition이 다음이 성립하는 집합 $G$를 말한다.

- associativite
- having a unit element
- having an inverse for $\forall x \in G$
	모든 $x \in G$에 대해 $xx^{-1} = x^{-1}x = e$를 만족하는 $x^{-1} \in G$ (inverse of $x$) 존재

여기서도 left inverse와 right inverse가 같음을 정의가 암시하고 있다. inverse가 유일함을 여기서도 확인할 수 있으며, unit element의 정의가 inverse의 정의보다 선행되어야 하는 것을 볼 수 있다.