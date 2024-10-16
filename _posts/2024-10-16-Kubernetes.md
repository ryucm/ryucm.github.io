---
tags:
  - K8s
---

# 전체 구조

![[Pasted image 20241003222059.png]]

# 쿠버네티스란?
---
- 컨테이너(애플리케이션)의 배포, 확장, 관리를 자동화하여 작업의 편의를 증대시킨다.

# 주요 구성
---
## [[Kubernetes_Master_Node|Master Node]]

### - [[Kubernetes_Master_Node#Kube-API-Server|Kube-API-Server]]
### - [[Kubernetes_Master_Node#Kube-Scheduler | Kube-Scheduler]]
### - [[Kubernetes_Master_Node#Kube-controller-manager | Kube-Controller-Manager]]

## [[Kubernetes_Worker_Node | Worker Node]]

# 객체 선언 방식
---
- 쿠버네티스는 사전에 우리가 정의한 객체를 관리한다.
- 객체를 정의하는 방식에는 **명령적 방식**과 **선언적 방식**이 있다.

## 명령적 방식
- deployment에 객체를 어떻게 관리할 것인지에 대한 상태값을 지정한다.
- 쿠버네티스는 deployment에 정해진 상태값에 따라 관리한다.

## 선언적 방식
