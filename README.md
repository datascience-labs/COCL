# COCL (Carbon Optimized Course Load)
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=Python&logoColor=white">

- **프로젝트명**: 탄소 발자국의 실시간 추적을 통해 캠퍼스 강의 스케줄의 Net-Zero 고도화
- **목표**: 대학 캠퍼스에서 각 강의실과 개별 PC에서 발생하는 전력 소모량(탄소 발자국)을 측정하고, 대학에서 생산 가능한 태양광 에너지 발전량(전력 생산량)을 예측한다. 이를 탄소중립 캠퍼스(Net-Zero) 구축을 위해 현실 가능성을 검토하고 현재 상황을 데이터로 시각화하여 모니터링 대시보드를 제공합니다. 
- **주요 컴포넌트**: COCL 프로젝트는 크게 3가지의 주요 컴포넌트로 구성됩니다. 첫 번째는 대학 캠퍼스의 재생에너지(전기) 발전량과, 캠퍼스의 전기 소모량을 강의실, 개별PC 단위로 측정하기 위한 **"캠퍼스의 탄소발자국 측정"** 컴포넌트, 전력소비 최적화를 위한 **"최적화 모듈"** 컴포넌트와 시각화 및 모니터링을 위한 **"모니터링 대시보드"** 컴포넌트로 구성됩니다. <br/><br/>

## 모니터링 대시보드 (Monitoring Dashboard)
- COCL App : Dash framework기반 Dashboard 구축 완료
![image](https://github.com/Prcnsi/COCL/assets/86015194/342a68ca-80d1-4e0d-84de-474df94b8946)
<br/>
<br/><br/><br/> 


## 캠퍼스의 탄소발자국 측정    
- COCL PM : 딥러닝을 사용하는 개별 PC와 강의실별 전력 소모량에 따른 탄소 배출량 측정 (백엔드 연동 API 코드)
- COCL PVwatts : 대학교 캠퍼스의 가상발전소(VPP, Virtual Power Plant)의 태양광 발전량(전기 생산량) 예측.<br/><br/><br/>

## 최적화 모듈 (Optimization Module)
- COCL Scheduling Processes : (생산-소비)pygenetic를 이용한 수업 스케쥴링 모듈을 개발
- BayesCOCL : 베이지안 네트워크와 COCL 결합<br/><br/><br/>

## 딥러닝모델의 탄소발자국 인증 (AI for Carbon)
- AI4Carbon-labels: 사용자의 AI 모델의 탄소발자국을 평가하기 위한 인증 스티커 개발하고 인공지능 모델을 학습 및 제공하는 서버에 부착하여 저탄소 AI 모델을 만들기 위한 기준을 제시합니다.


## Contributors

- COCL-APP Lead: [Prcnsi](https://github.com/Prcnsi)
- COCL-PVwatts Lead: [yeryeong713](https://github.com/yeryeong713), [yewon0325](https://github.com/yewon0325)
- COCL-PM Lead: [cpprhtn](https://github.com/cpprhtn)
- BayesCOCL Lead: [qor6](https://github.com/qor6)
- COCL-Scheduling Lead: [H-S-J](https://github.com/H-S-J)

<a href="https://github.com/datascience-labs/COCL/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=datascience-labs/COCL&columns=10" />
</a>
 
