# ※ 팀 소개
- 팀명 : 텐텐(10 x 10 = 100% !)
- 팀원 : 박동호(팀장), 이희진, 서예지, 유세빈, 최재현
- 평균나이 : 22.6세
- 컨셉 : 열정으로 똘똘뭉친 핏덩이들의 성장일기

# 인공지능 서비스 프로젝트 (2020.9.10~9.23)

## 1. 개요
- 주제 : 요리를 원하는 사람에게 쉽게 접할 수 있게 해주는 추천시스템
- 내용 : 코로나 사태를 맞이하여 집에서 머무는 사람이 많다. 집에 있으면 항상 끼니가 걱정인데, 배달은 비싸기도 하고 매번 시켜먹으면 질린다! 그렇기에 고안한 집에서 쉽게 요리를 해먹을 수 있도록 도와주는 서비스!
- 기능
  1. 원하는 요리를 검색하여 레시피를 찾을 수 있다.
  2. 냉장고에 있는 재료를 인풋으로 받아, 재료에 맞는 요리들을 추천 받을 수 있다.
  3. 영양소/질병 별 요리 추천
  4. 이후 기능 추가

## 2. 제안 배경 및 활용방안
- 제안 배경 : 봉지라면 수요 ↑ 집콕 ↑ 요리 교실의 한계 극복을 위함. 요리 관련 분야가 뜨고있다. 집밥을 해먹는 인구가 늘어나고 있는 상황. 전 세계적으로 집에서 요리를 해서 식사를 하는 것이 트랜드이다.
- 개발 필요성 : 코로나 사태를 맞이하여 집밖을 나서지 않는 사람이 많다. 집에 있으면 항상 끼니가 걱정인데, 배달은 매번 시켜먹으면 비싸기도 하고 질린다. 그렇기에 고안한 집에서 비교적 싸고 쉽게 요리를 해먹을 수 있도록 도와주는 서비스가 필요하다.
- 차별성 : 관련 사이트(해먹남녀 등)에서는 인풋 받은 재료가 모두 포함된 요리만 추천. 이 문제점을 해결하기 위해 유사도를 이용한 추천알고리즘을 사용하여 인풋 재료의 관련 정도에 따라 요리 추천.
- 기대효과 : 코로나를 기점으로 비대면 사회로 변화하므로, 이러한 트랜드에 맞춰 사용자들에게 요리에 대한 편리한 접근을 제공하려 함.
- 활용방안 : 1인가구와 같이 자취를 하는 사람 뿐만아니라, 요리가 필요한 모든 사람들에게 원하는 요리의 레시피를 제공하고, 막연히 요리를 해보고 싶어하는 사람에겐 추천을 통해 요리에 대한 흥미를 이끌 수 있다.

## 3. 프로젝트 순서도 및 일정

### 1. 모델링(각 기능을 구현한 모델 구축) & 데이터 전처리
- 2020 / 09 / 11(금) ~ 2020 / 09 / 16(수)
### 2. Django를 활용한 웹과 연동
- 2020 / 09 / 16(수) ~ 2020 / 09. / 18(금)
### 3. 오류 수정 및 기능 보완
- 2020 / 09 / 18(금) ~ 2020 / 09 / 21(월)
### 4. 발표자료 작성
- 2020 / 09 / 22(화) ~ 2020 / 09 / 23(수)
  
- - -

## Meeting Schedule
### 9.8(화)
#### 화상회의(11:00)
- 목표 : 각자 재료 인풋 받아 요리 추천하는 기능 구현한 결과물 공유

### 9.9(수)
#### 화상회의(11:00)
- 목표 : 각자 맡은 카테고리를 대표하는(이 음식을 보면 딱! 그 맛이 떠오른다 하는) 음식 하나 찾아오고 (요리이름 / 조리법 / 재료), 모든 종류의 요리법 데이터 찾아보기.

### 9.10(목)
#### 화상회의(10:00)
- 목표 : 기획서 마무리. 기능 구현 방안 고안, 한계시 다른 방안

### 9.11(금)
#### 화상회의(16:00)
- 목표 : 역할 분담한 각 기능 구현 / 결과 공유  
-> 구축한 모델의 정확도 문제 발생.

### 9.14(월)
#### 화상회의(17:20)
- 목표 : 모델 구축에 대한 구체적 방안, 결과 공유
