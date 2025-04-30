## 📘 프로젝트 설명

본 노트북은 자동차 사출성형 공정 데이터를 기반으로 불량을 예측하고 주요 원인을 분석하는 대시보드 구현을 위한 머신러닝 모델 개발 및 평가 과정을 담고 있습니다.  
사용된 데이터는 CN7(아반떼) 및 RG3(제네시스 G80) 부품의 공정 변수와 라벨 정보를 포함합니다.  
※ `unlabeled_data.csv`는 파일 용량(215MB)으로 인해 GitHub에는 업로드되지 않았습니다.

## 📁 필요 데이터 파일 목록

- `labeled_data.csv`: 전체 라벨링 데이터
- `labeled_cn7.csv`, `labeled_rg3.csv`: 각 부품별 라벨 데이터
- `unlabeled_data.csv`, `unlabeled_cn7.csv`, `unlabeled_rg3.csv`: 라벨 없는 공정 데이터 *(unlabeled_data.csv는 업로드 생략됨)*
- `Combined_Dataset_with_300_Synthetic_Fails.csv`: 증강 불량 포함된 합쳐진 데이터셋
- `Filtered__Only_Fail__N__Samples.csv`: 불량 샘플만 필터링한 데이터

---

## 📘 Project Description

This notebook develops and evaluates machine learning models to predict injection molding defects in automotive parts (CN7 & RG3), with an aim to deploy the results on a Streamlit-based dashboard.  
※ `unlabeled_data.csv` is not included in the repository due to its large size (215MB).

## 📁 Required Data Files

- `labeled_data.csv`: Full labeled process dataset
- `labeled_cn7.csv`, `labeled_rg3.csv`: Labeled data for each part type
- `unlabeled_data.csv`, `unlabeled_cn7.csv`, `unlabeled_rg3.csv`: Raw process data without labels *(unlabeled_data.csv not uploaded)*
- `Combined_Dataset_with_300_Synthetic_Fails.csv`: Combined dataset including 300 synthetic defect samples
- `Filtered__Only_Fail__N__Samples.csv`: Only defective (N) samples extracted
