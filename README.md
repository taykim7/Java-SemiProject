# [ 세미 프로젝트 ] 쉽게 매장을 관리할 수 있는 『 무인 편의점 키오스크 』
<br>
비전공자끼리 이루어진 팀원들과 영혼까지 끌어모아 완성한 첫 프로젝트!
<br><br>
🛒 <b>기간</b> : 2022년 2월 8일 ~ 14일 (6 days)
<br><br>
🛒 <b>사용언어</b> : only <b>JAVA</b>
<br><br>
🛒 <b>주제 선정</b> : 무인 편의점 키오스크
<br><br>
🛒 <b>선정 이유</b> : 언택트 시대에 맞춰 무인매장 확대가 예상되어 <b>무인 편의점 키오스크</b>를 기획하려 했습니다!😉
<br><br>
🛒 <b>기능</b><br><br>
<table border="1" data-ke-align="alignLeft">
<tbody>
<tr style="height: 22px;">
<td style="width: 50%; height: 132px;" rowspan="6"><span style="color: #000000;"><b>공통 기능</b></span></td>
<td style="width: 50%; height: 22px;"><span style="color: #000000;">상품 구매 (상품 선택 &rarr; 카테고리 선택 &rarr; 재고 선택)</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">장바구니 (장바구니 확인, 구매, 비우기)</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">결제 (현금결제, 잔액결제) ... 잔액결제는 회원만 가능!</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">영수증 출력</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">주민번호 유효성 검사</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">성인 인증</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 100%; height: 22px;" colspan="2">&nbsp;</td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 66px;" rowspan="3"><span style="color: #000000;"><b>이용자 모드 기능</b></span></td>
<td style="width: 50%; height: 22px;"><span style="color: #000000;">회원가입</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">로그인</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">잔액 충전</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 100%; height: 22px;" colspan="2">&nbsp;</td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 88px;" rowspan="4"><span style="color: #000000;"><b>관리자 기능</b></span></td>
<td style="width: 50%; height: 22px;"><span style="color: #000000;">관리자용 로그인</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">프로그램 종료 (오직 이 기능으로만 종료할 수 있다)</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">매출 관리 (전체 매출, 카테고리별 매출)</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 50%; height: 22px;"><span style="color: #000000;">재고 관리 (상품 추가, 수량 변경, 삭제)</span></td>
</tr>
</tbody>
</table>

<br><br>
🛒 <b>플로우차트</b><br><br>
<img width="100%" src="https://user-images.githubusercontent.com/97800846/170993215-39d10a62-bc11-4e64-9fb3-1a65a62b1299.png"/>

<br><br>
🛒 <b>주요 클래스 및 메소드</b><br><br>
<img width="100%" src="https://user-images.githubusercontent.com/97800846/170993954-c9e76b8c-526f-40ec-9fdc-add489d19eec.png"/>

<br><br>
🛒 <b>Purchase class - 물품선택 및 구매가능 수량 확인</b><br><br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170997692-a3c0cc52-8ed5-4976-8c91-faa7ee64c158.png"/>
<br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170997705-99dd533d-eded-47da-a3be-30ee0ace2763.png"/>

<br><br>
🛒 <b>Cart class - 장바구니 확인</b><br><br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170998508-a8b09f61-1668-407e-bbf6-b7cdee86bd99.png"/>
<br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170998517-96754a02-492b-40b1-b042-b852213e7aef.png"/>

<br><br>
🛒 <b>Buy class - 현금 결제</b><br><br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170999138-934cadd9-bc62-4232-a7a4-34a2d5091c99.png"/>
<br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170999147-68a1f801-8340-4035-bf95-d96b9e8a1d99.png"/>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170999155-9b06d34f-5a15-4472-b6b7-692402ae8fa9.png"/>
<br>
주요변수 - int sumCash : 누적 투입 현금 / int returnCash : 거스름돈

<br><br>
🛒 <b>Buy class - 잔액 결제</b><br><br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170999969-82475697-c775-4f89-b817-fb958833402c.png"/>
<br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/170999979-e9300a6d-0778-4c0e-99e1-64c3f5408b70.png"/>
<br>
주요변수 - static int totPrice : 물품 총 금액

<br><br>
🛒 <b>AdSystem class - 재고입력/변경/삭제</b><br><br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/171000904-5d1b54d5-b9ee-47f6-af69-87c37b24d424.png"/>
<br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/171000909-502964b8-4d62-47f3-aecf-47c9e289cd4d.png"/>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/171000920-044d5b67-d8e0-4a62-8485-f1d1d36788bc.png"/>

<br><br>
🛒 <b>AdSystem class - 매출관리</b><br><br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/171001392-bb01002b-1634-4578-ae9d-f1cdaa06f114.png"/>
<br>
<img width="50%" src="https://user-images.githubusercontent.com/97800846/171001403-a0eeb33c-1b71-4c84-baf3-73850a61b165.png"/>

<br><br>

🛒 <b>후기</b><br>
세미 프로젝트를 진행해 보니<br>
처음엔 모두가 뭐부터 시작해야 할지를 몰라서 막연했던 게<br>
이제는 어떻게 진행되는 알 수 있었고 팀원들 모두의 실력도 발전하는 게 보였습니다.<br>
또한 DB와 Git에 대한 갈증을 느낄 수 있었습니다.<br>
어려웠고 힘들었지만 코딩의 재미를 느낄 수 있었던 첫 프로젝트였습니다!<br>


<br><br>
