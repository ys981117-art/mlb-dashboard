# MLB 카테고리 판매 분석 대시보드

실시간 판매 데이터 분석 대시보드를 제공합니다.

## 📊 주요 기능

- **카테고리별 판매 현황**: OUTER, INNER, BOTTOM 그룹별 분석
- **시계열 분석**: 주차별 판매 추이 분석
- **속성 분석**: 중량감, 핏, 기능성 등 속성별 판매 분석
- **VOC 분석**: 고객 의견 분석
- **ST (판매율)**: 입고수량 대비 판매수량 분석

## 🚀 접속 방법

GitHub Pages를 통해 배포된 대시보드에 접속하세요:
- **메인 페이지**: `https://[사용자명].github.io/[저장소명]/`

## 📁 파일 구조

```
.
├── index.html              # 대시보드 메인 파일 (모든 데이터 포함)
├── preprocess_data.py      # 데이터 전처리 스크립트
├── create_standalone_dashboard.py  # 독립 실행형 대시보드 생성
└── README.md              # 이 파일
```

## 🔄 데이터 업데이트 방법

1. 데이터 파일 업데이트 (CSV 파일들)
2. 전처리 스크립트 실행:
   ```bash
   python preprocess_data.py
   ```
3. 독립 실행형 대시보드 생성:
   ```bash
   python create_standalone_dashboard.py
   ```
4. `index.html` 파일이 업데이트됨
5. GitHub에 커밋 및 푸시:
   ```bash
   git add index.html
   git commit -m "데이터 업데이트"
   git push
   ```

## 📝 사용 기술

- Chart.js: 차트 시각화
- Plotly: 3D 그래프
- Vanilla JavaScript: 대시보드 로직

## 📧 문의

문제가 발생하거나 개선 사항이 있으면 이슈를 등록해주세요.

