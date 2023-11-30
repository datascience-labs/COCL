# COCL (Carbon Optimized Course Load)
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=Python&logoColor=white">


- **프로젝트명**: 탄소 발자국의 실시간 추적을 통해 캠퍼스 강의 스케쥴의 Net-Zero 고도화
- **목표**: 대학 캠퍼스에서 각 강의실과 개별 PC에서 발생하는 전력 소모량(탄소 발자국)을 측정하고, 대학에서 생산 가능한 태양광 에너지 발전량(전력 생산량)을 예측한다. 이를 탄소중립 캠퍼스(Net-Zero) 구축을 위해 현실 가능성을 검토하고 현재 상황을 데이터로 시각화하여 모니터링 대시보드를 제공합니다. 
- **주요 컴포넌트**: COCL 프로젝트는 크게 3가지의 주요 컴포넌트로 구성됩니다. 첫 번째는 대학 캠퍼스의 재생에너지(전기) 발전량과, 캠퍼스의 전기 소모량을 강의실, 개별 PC 단위로 측정하기 위한 **"캠퍼스의 탄소발자국 측정"** 컴포넌트, 전력 소비 최적화를 위한 **"최적화 모듈"** 컴포넌트와 시각화 및 모니터링을 위한 **"모니터링 대시보드"** 컴포넌트로 구성됩니다. <br/><br/>
  

## 캠퍼스의 탄소발자국 측정
- COCL PM : 딥러닝을 사용하는 개별 PC와 강의실별 전력 소모량에 따른 탄소 배출량 측정 (백엔드 연동 API 코드)
- COCL PVwatts : 대학교 캠퍼스의 가상발전소(VPP, Virtual Power Plant)의 태양광 발전량(전기 생산량) 예측.<br/><br/><br/>


## 최적화 모듈 (Optimization Module)
- COCL Scheduling Processes : (생산-소비)pygenetic를 이용한수업 스케쥴링모듈 개발
- BayesCOCL : 베이지안 네트워크와 COCL 결합<br/><br/><br/> 


## 모니터링 대시보드 (Monitoring Dashboard)
- COCL App : Streamlit 기반 Dashboard 개발 (PM, PVWatts App에 붙이기)
- COCL Admin : Streamlit 기반 관리자용 프로그램 개발<br/><br/>
![image](https://github.com/Prcnsi/COCL/assets/86015194/4d8f1df3-2872-488b-9b57-d6ff333f3e7f)<br/>
```*예시(출처: https://www.finereport.com/kr/%EC%8B%9C%EA%B0%81%ED%99%94-%EB%8C%80%EC%8B%9C%EB%B3%B4%EB%93%9C/)```
<br/><br/><br/>
   

 


