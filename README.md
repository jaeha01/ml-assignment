# ml-assignment
이 프로젝트는 Titanic 데이터를 분석하여 생존 여부에 영향을 미치는 요인을 파악하는 것을 목표로 합니다.  
Python과 다양한 데이터 분석 라이브러리를 활용하여 탐색적 데이터 분석(EDA), 시각화, 및 모델링을 수행합니다.

## **프로젝트 구조**

- `data/` : 데이터 파일이 위치한 디렉토리
- `notebooks/` : Jupyter Notebook 파일이 위치한 디렉토리
- `src/` : 데이터 처리 및 모델링 스크립트 코드
- `README.md` : 프로젝트 설명 파일
- `pyproject.toml` : Python 환경 및 의존성 관리 설정 파일

---

## **분석 내용**

1. **탐색적 데이터 분석 (EDA)**  
   - 결측치 처리
   - 변수 간 상관관계 분석
   - 생존 여부에 따른 변수 시각화

2. **모델링**  
   - 데이터 전처리
   - 머신러닝 알고리즘 적용 (예: 로지스틱 회귀, Random Forest,나이브 베이즈 분류, 서포트 벡터 머신)
   - 모델 평가

3. **결과 해석**  
   - 주요 영향 요인 도출
   - 모델 결과 비교

---

## **개발 환경**

- **운영체제**: macOS
- **Python 버전**: 3.10
- **필수 라이브러리**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter notebook

---

## **사용 방법**

1. Python 가상 환경 설정 및 활성화
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
