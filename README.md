## 1. 팀소개 
### 팀명 : 

## 팀원 소개
| 주수빈 | 임산별 | 박민정 | 김준협 | 김수현 |
|---|---|---|---|---|
| <img width="150" height="150" src="" /> | <img width="150" height="150" src="" /> | <img width="150" height="150" src="" /> | <img width="150" height="150" src="" /> | <img width="150" height="150" src="" /> |
|[@Subin-Ju](https://github.com/Subin-Ju)|[@ImMountainStar](https://github.com/ImMountainStar)|[@minjeon](https://github.com/minjeon)|[@use08168](https://github.com/use08168)|[@K-SH98](https://github.com/K-SH98)|

## 🔨 2. 프로젝트 개요 

### <📛 프로젝트 명>


### <📌 프로젝트 소개>


### <🚀 프로젝트 배경>


### <🎯 프로젝트 목표>



## 🛠️ 3. 기술스택
| **분류**         | **기술/도구**                                                                            |
|------------------|------------------------------------------------------------------------------------------|
| **언어**         | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">     |
| **라이브러리**   | ![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy)       ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas)   <img src="https://img.shields.io/badge/Matplotlib-CB3B27?style=for-the-badge&logo=matplotlib&logoColor=white">  | 
| **머신러닝**     | <img src="https://img.shields.io/badge/Scikit-learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
| **협업 툴**      | <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">


## 4. WBS




## 🗂️ 5. 원본 데이터에 대한 분석
### 5-1. 원본 데이터 소개
| **데이터 이름**   |   **파일 형식 / 수집 방법**    |   **데이터 출처**      |
|:-----------------:|:-----------------------------:|:---------------------------------:|
| 대학교 강의 수강 데이터 |  csv / 직접 다운로드 | https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset |


- 본 데이터셋(Open University Learning Analytics dataset, OULAD)은 영국 오픈 유니버시티 학생들의 학습 활동과 성적, 강의 수강 정보, 그리고 온라인 학습 환경(VLE; Virtual Learning Environment)에서의 상호작용 데이터를 포함하고 있습니다.
- 구체적으로, 7개의 강의(`code_module`)에 등록한 30,000명 이상의 학생들의 데이터를 다루며, 강의 정보 / 학생 정보 / 온라인 활동 / 과제 제출 및 평가 / 등록 및 이탈 등과 관련된 여러 csv 파일로 구성되어 있습니다.


**활용한 데이터** : student_Info.csv


### 5-2. 원본 데이터 분석
![수행결과 이미지](image/studentInfo.png)


#### 총 11개의 feature 컬럼 
| **컬럼 명** |     **컬럼 소개**   |  **컬럼 데이터 타입** |
|:-------------------:|:--------------------------------:|:------------:|
| code_module | 등록 강의 | object |
| code_presentation | 강의가 개설된 학기 구분 코드 | object |
| id_student | 학생 고유 ID | int64 |
| gender | 성별 | object |
| region | 거주 지역 | object |
| highest_education | 최고 학력 | object |
| imd_band | 다중 빈곤 지수(= 한국의 소득 1~10분위) | object |
| age_band | 연령대 | object |
| num_of_prev_attempts | 재수강하는 강의 수 | int64 |
| studied_credits | 현재 수강 학점 | int64 |
| disability | 장애 여부 | object |



**target 컬럼 : 탈퇴 여부** `final_result`  
: final_result는 총 4개의 결과값( `Withdrawn(탈퇴)` / `Fail(낙제), Pass(통과), Distinction(우수 수료)` )가 존재함.


## 🖥️ 6. 데이터 전처리 결과서 (EDA)


## 🦾 7. 인공지능 학습 결과서


## ✏️ 8. 수행결과(테스트 결과 화면 또는 시연 페이지)


## 9. 한계점 및 보완점


##  😎**팀원 한 줄 회고**
|이름|내용|
|:---:|:---|
| 주수빈 | |
| 임산별 | |
| 김민정 | |
| 김준협 | |
| 김수현 | |

