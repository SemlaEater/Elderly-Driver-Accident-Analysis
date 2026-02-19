# 📌 Elderly Driver Accident Analysis

## 1. 문제 정의
- 댓글과 언론에서 고령 운전자임을 강조하는 현상에 의문이 들어, 실제로 고령 운전자의 사고가 늘어났는지, 고령 운전자 가해 사고의 비율이 다른 연령대에 비해 높은지 궁금해서 분석하게 되었음<br>
## 2. 데이터
- 한국도로교통공단 교통사고분석시스템 ,'https://taas.koroad.or.kr/sta/acs/exs/typical.do?menuId=WEB_KMP_OVT_UAS_ASA'
- KOSIS 운전면허소지자현황(연령대별), 'https://kosis.kr/statHtml/statHtml.do?sso=ok&returnurl=https%3A%2F%2Fkosis.kr%3A443%2FstatHtml%2FstatHtml.do%3Fconn_path%3DI3%26tblId%3DDT_13201_A002%26orgId%3D132%26'
## 3. 분석 과정
- 공공데이터를 활용한 연령대별 교통사고 및 면허 데이터 수집 및 전처리<br>
- 연령대별 면허 소지자 대비 가해 운전자 사고 발생률 지표 생성<br>
- 시계열 분석을 통한 연령대별 사고 발생률 변화 추이 비교<br>
- 고령 운전자 사고 증가 현상을 총량과 사고율 관점에서 분리해 해석<br>
## 4. 결과
- 65세 이상 연령대는 최근 몇 년간 면허 소지자 대비 사고 발생률이 다른 연령대보다 빠르게 증가하는 경향을 보임<br>
- ‘한국 사회의 초고령화로 사고가 늘었다’는 해석으로 보기 힘든 사고 위험 증가가 보임<br>
- 분석 과정에서 개인 단위의 반복 사고 등 데이터의 한계<br>

## 5. 사용기술
- Python, Pandas, Matplotlib
