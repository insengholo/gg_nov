# gg_nov — Gemini 2.5 기반 피싱 이메일 분석 데모
Google Gemini 2.5 Flash를 REST/Gradio로 호출해 이메일 본문을 분석하고  
`risk_score / decision / evidence / recommended_actions` 형태의 JSON 결과를 생성.

## 실행 방법(Colab)
1) `gg_nov.ipynb` 열기 → 셀 1, 2, 3 순서대로 실행  
2) 셀 1에서 GEMINI_API_KEY를 입력
3) 마지막 셀에서 뜨는 Gradio 링크 클릭 → 데모 사용

## 요구 패키지
1) gradio
2) requests
