# CJ-Delivery-EDA

## Requirement
- python 3.9.x 버전 사용
- `pip install -r requirement.txt`로 라이브러리 설치 후 사용
- 라이브러리 추가 시 `push` 하기 전에 `pip freeze > requirement.txt`로 업데이트 후 `push`

## Data
- `root` 폴더에 `data` 폴더 생성 후 `data` 폴더에 `xlsx` 파일 추가 후 사용
- `xlsx` 파일 `배송 -> delivery`, `집화 -> collect`로 이름 변경 후 사용
- `data` 폴더는 `.gitignore`로 `push` 불가능 하기 때문에 자유롭게 생성 후 사용

## JSON 파일 저장
- 'result` 폴더에 생성된 JSON 파일 저장

## 디렉토리 구조
```bash
CJ-Delivery-EDA
├── data
│   ├── delivery.xlsx
│   └── collect.xlsx
│── result
│   ├── delivery.json
│   └── collect.json
└── EDA.py or EDA.ipynb
``` 

## 주의사항
- 반드시 `branch` 생성 후 작업 할 것
- `main`에 `push` 및 `PR` 금지
