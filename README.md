# Korean-Table-LM-Probe


한국어 표 언어모형의 지식 검증(LAMA Probe)을 위한 코드입니다.

본 코드에서는 구축된 언어모형의 지식 검증을 위한 지식베이스 데이터셋으로 다음 2가지 데이터셋을 사용하였습니다.

AIHub의 약관 때문에 데이터셋은 아래의 정보를 통해서 다운받은 후 데이터 정제 코드를 이용하여주시기 바랍니다.\

-일반 상식 지식베이스
https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=106

-정신건강(우울증, 불안장애) 기반의 의미의 구축
https://aihub.or.kr/aihubdata/data/view.do?currMenu=120&topMenu=100&aihubDataSe=extrldata&dataSetSn=285

데이터 정제 코드에서는 트리플의 Object가 단일 토큰으로 구성된 데이터만 정제하고 평가 코드에 맞는 포멧으로 데이터 파일을 생성합니다.


![image](https://user-images.githubusercontent.com/11895148/185902555-e8c2a451-6fd9-4a26-aa02-5e63308dcb5a.png)
표 언어모형에 대한 LAMA 검증 방법


![image](https://user-images.githubusercontent.com/11895148/185903769-2e6385f9-b6dc-4639-bf1e-b6b03e040113.png)
표 언어모형의 지식 검증 실험 결과
