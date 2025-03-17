## 도커와 주피터를 이용한 pandas 활용

# 📊 Pandas for Finance Data - Series & DataFrame

이 프로젝트는 금융 데이터를 다루는 데 유용한 **Pandas 라이브러리**를 사용하여 **Series 및 DataFrame**의 개념을 학습하는 Jupyter Notebook입니다.

## 📌 개요
Pandas의 핵심 데이터 구조인 **Series**를 학습
Python을 활용하여 금융 데이터를 효과적으로 분석할 수 있도록 기초적인 내용

## 📖 주요 내용
### 🔹 Series란?
- **Series**는 **1개의 컬럼**을 가지는 데이터 구조로, **인덱스와 값**으로 구성됩니다.
- 리스트, 딕셔너리, 넘파이 배열 등 다양한 형태의 데이터를 Series로 변환할 수 있습니다.

#### ✔ Series 생성 예제
```python
# 판다스 라이브러리 불러오기
import pandas as pd

# 리스트를 Series로 변환
ls1 = [1, 2, 3, 4, 5, 6, 7, 8, 9]
sr1 = pd.Series(ls1)
print(sr1)

# 다양한 데이터 타입을 포함한 리스트
ls2 = [1, 2, 3, 'Apple', 'play', 6, 7, 8, 9]
sr2 = pd.Series(ls2)
print(sr2)
```

## 🛠 실행 방법
1. **필수 라이브러리 설치**
   ```bash
   pip install pandas jupyter
   ```
2. **Jupyter Notebook 실행**
   ```bash
   jupyter notebook
   ```

## 📌 적용 분야
- 금융 데이터 분석
- 시계열 데이터 처리
- 주식 및 암호화폐 가격 데이터 활용
