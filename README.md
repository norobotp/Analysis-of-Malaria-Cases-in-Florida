# 🦟 Analysis of Malaria Cases in Florida

This project investigates the transmission dynamics of malaria in Florida using a spline-based SEIR (Susceptible–Exposed–Infectious–Recovered) model with seasonal and immigration covariates.

## 🔍 Overview
We built a stochastic compartmental model in **R** using the `pomp` package to:
- Simulate malaria spread under varying climate and migration conditions
- Estimate key epidemiological parameters
- Evaluate model performance using particle filtering and likelihood profiles

## 📈 Key Features
- **Spline-based transmission modeling**: Captures seasonality in malaria spread  
- **Iterated filtering (mif2)** for parameter optimization  
- **Profile likelihood** and **simulation-based confidence intervals** to assess uncertainty  
- **Parallel computation** with `foreach` and `doFuture` for scalable inference  
- Visualization of simulated trajectories against real data for model validation

## 📁 Output
The HTML report includes:
- Model specifications and assumptions  
- Parameter estimation process  
- Simulations of outbreak trajectories  
- Comparative model diagnostics

## ⚙️ Technologies Used
- `R`, `pomp`, `ggplot2`, `foreach`, `doFuture`  
- SEIR modeling, Bayesian inference, stochastic simulation

---

## 💡 Motivation
This analysis was part of a graduate-level data science course project at the University of Michigan, aimed at understanding how **seasonal factors** and **external immigration** affect vector-borne disease dynamics in a non-endemic region.

---

# 🦟 플로리다 말라리아 발생 분석

본 프로젝트는 **계절성과 외부 유입(이주)** 변수를 반영한 **spline 기반 SEIR (Susceptible–Exposed–Infectious–Recovered)** 모델을 통해, **플로리다 지역의 말라리아 전파 동역학**을 분석한 것입니다.

---

## 🔍 개요

`pomp` 패키지를 활용해 R에서 확률적 구획 모델을 구축하여 다음을 수행하였습니다:

- 기후 및 이주 조건 변화에 따른 말라리아 확산 시뮬레이션  
- 주요 전염병학적 파라미터 추정  
- 입자 필터링과 가능도(profile likelihood) 기반 모델 평가  

---

## 📈 주요 특징

- **스플라인 기반 전염률 모델링**: 계절성(예: 여름철 감염 증가)을 정교하게 반영  
- **Iterated filtering (mif2)**: 반복 필터링을 통한 파라미터 최적화  
- **Profile likelihood 분석** 및 **시뮬레이션 기반 신뢰구간** 추정  
- **병렬 연산(foreach + doFuture)**을 통해 추론 계산 시간 단축  
- 실제 데이터와 시뮬레이션 결과를 시각적으로 비교하여 모델 적합도 검증  

---

## 📁 결과물

HTML 분석 보고서에는 다음이 포함됩니다:

- 모델 가정 및 수식 설명  
- 파라미터 추정 과정 및 진단 지표  
- 말라리아 확산 시뮬레이션 결과  
- 다양한 모델 간 성능 비교  

---

## ⚙️ 사용 기술

- `R`, `pomp`, `ggplot2`, `foreach`, `doFuture`  
- SEIR 구획 모델링, 베이지안 기반 추론, 확률 시뮬레이션  

---

## 💡 프로젝트 동기

이 분석은 **미시간대학교 데이터 과학 대학원 수업**의 프로젝트로 수행되었으며, **비유행(non-endemic) 지역에서 계절성 및 외부 유입 요인이 모기 매개 질병 전파에 미치는 영향**을 이해하는 데 목적이 있습니다.

