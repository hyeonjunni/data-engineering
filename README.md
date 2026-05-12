# 데이터 엔지니어링 실습 기록

2026학년도 1학기 데이터 엔지니어링 수업의 실습 노트북과 예제 데이터를 정리한 저장소입니다.

## 환경

- Python 3.13.12
- Jupyter Notebook
- 주요 라이브러리: NumPy, pandas, matplotlib, scikit-learn

## 폴더 구조

```text
.
├── data/                 # 실습용 CSV 데이터
├── *.ipynb               # 주차별 실습 노트북
├── requirements.txt      # Python 패키지 목록
└── README.md             # 저장소 안내
```

## 실습 노트북

| 파일 | 내용 |
| --- | --- |
| `01_numpy_arrays.ipynb` | NumPy 배열 기초 |
| `02_numpy_ufunc.ipynb` | NumPy 유니버설 함수 |
| `03_numpy_advanced.ipynb` | NumPy 고급 기능 |
| `04_pandas_objects.ipynb` | pandas Series, DataFrame, Index |
| `05_data_manipulation.ipynb` | pandas 데이터 조작 |
| `06_combining_datasets.ipynb` | 데이터 병합과 결합 |
| `07_eda_inst.ipynb` | 탐색적 데이터 분석 |
| `08_web_scraping.ipynb` | 웹 스크래핑 |
| `09_restful_api_inst.ipynb` | RESTful API 활용 |
| `10_working_with_time_series.ipynb` | 시계열 데이터 기초 |
| `11_timeseries_specific_operations.ipynb` | 시계열 특화 연산 |
| `12_handling_missing_data.ipynb` | 결측치 처리 |
| `13_missing_data_imputation.ipynb` | 결측치 대체 |

## 데이터

`data/` 폴더에는 실습에 사용하는 CSV 파일이 들어 있습니다.

- `AirQualityUCI_refined.csv`
- `moldset_labeled_cn7_missing.csv`
- `seattle2014.csv`

## 실행 방법

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

이후 Jupyter Notebook 환경에서 원하는 `.ipynb` 파일을 열어 실행합니다.

## Git 관리 기준

- 수업 노트북과 필요한 예제 데이터만 GitHub에 올립니다.
- `.ipynb_checkpoints/`, `.DS_Store`, 가상환경 파일은 Git에서 제외합니다.
