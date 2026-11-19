# recipe-recommender

Data Literacy Foundations final project : 보유 재료 기반 레시피 추천

## 데이터
식품의약품안전처 조리식품의 레시피 DB (COOKRCP01)
- https://www.foodsafetykorea.go.kr/api/openApiInfo.do?svc_no=COOKRCP01
- 레시피 1,156개 (2026.11.19 기준)

데이터 파일은 올리지 않았습니다. 식품안전나라에서 인증키를 받은 후, 아래 주소로 가서 파일을 받아서 `data/` 폴더에 저장하시면 됩니다.

```
https://openapi.foodsafetykorea.go.kr/api/{인증키}/COOKRCP01/json/1/1000      -> data/recipes_1_1000.json
https://openapi.foodsafetykorea.go.kr/api/{인증키}/COOKRCP01/json/1001/2000   -> data/recipes_1001_2000.json
```

## 실행
```
pip install pandas numpy matplotlib jupyter
jupyter notebook data_exploration.ipynb
```
결과(요약표, 그래프)는 `outputs/`에 저장됩니다.
