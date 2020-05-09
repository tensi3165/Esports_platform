# E-Sports Integrated Management Platform
> 2019.05.29 - 2019.10.11

E-sports 통합 관리 시스템

## TEAM ULTIMATE
TEAM ULTIMATE에 대해 간단히 소개를 하자면 
부산정보산업진흥원 소속 부산e스포츠협회의 대회 운영 관련문제를 해결하기위해
부산대학교 중앙동아리 ULTIMATE와 정보컴퓨터공학부 학술동아리 UNTOC이 연합하여 결성된 팀입니다.

## 프로젝트 개요

현재 부산의 E-sports 대학 리그나 부산대 내의 E-sports 관련 대회 진행에 있어서 원활하고 빠른 대회 진행을 위해 웹 기반의 E-sports 대회 통합 관리
플랫폼을 제안합니다. 이를 통해서 주최자 측은 간편하게 대회를 등록, 부수적으로 연습경기 (스크림) 매칭을 이용할 수 있도록 합니다.

프로젝트의 자세한 개요를 보시려면 E-sport_platform 제안서.pdf 를 열람해주세요.

프로젝트 결과 요약을 보시려면 착한창의종합설계_발표자료_TEAMULTIMATE .pdf 를 열람해주세요.

## 기능
1. 이스포츠 대회 특성상 다양한 종목이 있고 다양한 형태의 대회가 존재하는 만큼 플랫폼에서 다양한 대회를 지원해야합니다. 

2. 대회별로 선수등록에대해 확고한 규정이 존재하기 때문에 선수 등록부터 선수 이적에 관련한 로스터 관리 시스템을 구현해야 합니다. 

3. 대진표를 이미지 형태로 제공하는 것이 가장 낫다고 판단하여 대진표 렌터링 프로그램을 구현해야합니다. 

4. 경기가 종료된후 경기별 스코어나 선수별 스탯을 일일이 수작업으로 기록하는 것은 매우 번거로운 작업이므로 전적 api를 개발하여 경기별 전적 관리를 쉽게 하도록 해야합니다. 

5. 대회전 많은 팀들이 비슷한 수준의 팀들과 연습경기를 갖고 싶어하는 점에 주목하여 원하는 상대의 실력대나 시간을 입력하면 연습경기를 주선해주는 스크림 매칭 시스템을 구현해야합니다. 

따라서, 이스포츠 통합 관리 플랫폼의 차별성으로는, 대회의 운영과 관리 자동화, 스크림 매칭 시스템, 선수 모집 기능이 있습니다. 

## 기대효과 및 활용방안

현재 다양한 E-Sports 대회가 진행되고 있으며 앞으로 더 많은 E-Sports 대회가 활성화 될 예정인 만큼 저희 팀에서 진행할 프로젝트인 “E-Sports 대회 통합 관리 플랫폼”은 다양한 분야에 활용될 것으로 예상됩니다. 대동제의 경우 일정이 빠듯한 관계로 플랫폼 적용에 시간적 무리가 있으나 올해 10월에 있을 학과별 대회를 통해 플랫폼을 테스트하고 내년부터 적용할 수 있을 것으로 보입니다.  또한 중앙동아리 ULTIMATE에서 기획중인 부산대학교 하계 동계 E-Sports 리그 및 동아리 내부대회에 적용될 예정입니다. 성공적으로 테스트가 끝나면, 부산 E-sports 협회(BeSPA)에서 주관하는 부산 e-sports 대학 리그에 적용할 계획입니다.

## 프로젝트 경과

### 분석 및 기획 ~ 2019.06.18

자료수집, 시장조사, 관계자 인터뷰, 컨셉 정의, 기능 정의

### 프로젝트 설계 ~ 2019.07.31

세부 기능 정의, 핵심 모듈 정의, 디자인 기획, DB스키마 정의, 서버 설계

### 개발  2019.08 ~ 2019.09

개발환경 구축, 웹 개발, 핵심 모듈 개발, DB 구축

> 백엔드 개발 담당이 중간에 사고를 당해 팀에서 하차하며 백엔드 로직 구축 실패(서버사이드)

### 테스트 ~ 2019.10.05

반응형 웹, 핵심 모듈 구동 테스트

프로젝트가 엎어졌지만 공모전 제출물은 만들어야 했기에 프론트엔드, 모듈만을 구성해 결과물 테스트(로컬에서만 구동됨)

### 피드백 ~ 2019.10.11

백엔드 구축이 안되 페이지 로직을 구현 못한것이 너무 아쉽지만 웹에 대한 공부를 굉장히 많이 할 수 있었음.
또한 초보적이라 공모전에서는 구현할 수 없었지만 파이썬 Django에 대해 알게 되었고 사용법을 대강 파악할 수 있었음.

아이디어와 설계부분에서 굉장히 좋은 평을 받아 장려상을 수상했지만, 앞으로 웹 공부를 좀 더 해서 제대로 완성시키고 싶음.
