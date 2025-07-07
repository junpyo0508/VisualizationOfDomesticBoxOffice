# 🎬 국내 박스오피스 가중치에 따른 매출액 시각화  
**Visualization of Domestic Box Office Sales by Weight**

본 프로젝트는 2000년부터 2023년까지의 국내 박스오피스 데이터를 수집·가공하여, 영화 장르와 흥행 성적의 흐름을 시각적으로 분석할 수 있는 대시보드 웹사이트입니다. 사용자 중심의 인터랙티브 기능을 통해 영화 흥행 데이터를 연도별, 장르별, 매출액 기준으로 탐색할 수 있으며, 스택 영역 차트(Stacked Area Chart), Polar Bar Chart 등을 통해 시기별 트렌드를 직관적으로 이해할 수 있습니다.

![포폴](https://github.com/user-attachments/assets/7e6d46db-3d8b-4a03-9201-8d5b603d3c40)

[링크] https://junpyo0508.github.io/VisualizationOfDomesticBoxOffice/

## 프로젝트 개요

- **목표**  
  복잡한 영화 산업 데이터를 직관적으로 전달하여, 사용자가 직접 가중치를 조정하며 흥행 트렌드 분석을 경험할 수 있는 웹 기반 시각화 툴 제작.

- **주요 기능**
  - 연도별 영화 매출 흐름 시각화
  - 장르별 매출액 및 영화 수 비교
  - 인터랙티브한 가중치 조정 기능
  - 주요 영화에 대한 상세 데이터 제공

## 주요 시각화 요소

- **Stacked Area Chart**: 연도별 장르 비중 및 매출 흐름을 시간축에 따라 시각화  
- **Polar Bar Chart**: 장르별 매출과 작품 수를 동시에 반영하여 구조적 비교 가능  
- **Bar Chart**: 전체 기간 기준으로 흥행 순위 영화 정렬

## 사용 기술

- **Frontend**: HTML, CSS, JavaScript  
- **Visualization**: D3.js, Chart.js  
- **Data Preprocessing**: Python (Pandas, NumPy)  
- **Data Source**: KOBIS, CGV, Naver Movie 등 공개 API 및 수작업 정리

## 사용법

1. 해당 저장소를 클론하거나 [GitHub Pages 링크]로 접속합니다.  
2. 메인 화면에서 원하는 연도 및 장르를 선택합니다.  
3. 가중치를 조정하여 시각화 결과가 어떻게 달라지는지 확인합니다.  
4. 주요 영화를 클릭하면 상세 정보가 제공됩니다.

## 유저 시나리오

사용자는 자신이 관심 있는 장르나 특정 시기를 선택하여, 그 당시 어떤 영화들이 흥행했는지, 어떤 장르가 주류였는지를 시각적으로 탐색할 수 있습니다. 이를 통해 영화 산업의 흐름, 사회적 사건에 따른 관객 반응 등을 직관적으로 이해할 수 있습니다.

## 결과 요약

- 특정 시기(2019, 2023)에 애니메이션·판타지 장르가 강세를 보임  
- 팬데믹 기간 동안 SF·스릴러 장르의 비중이 급감  
- 대중성과 수익성 사이의 상관관계를 다양한 방식으로 비교 가능

## 데이터 출처

- KOBIS 영화진흥위원회 통합전산망  
- CGV 박스오피스 차트  
- 네이버 영화 정보  

## 참고 문헌

1. Alexander Vartanov, *Movie Waves*, 2020  
2. Matthew Boch, Amanda Cox, *The Ebb and Flow of Movies*, 2006–2008

---

> 본 프로젝트는 아주대학교 디지털미디어학과 수업의 일환으로 제작되었습니다.  
