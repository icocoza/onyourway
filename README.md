# onyourway
배송 주문 예약 서비스 

# Order & Deliver
1. 앱실행
2. 로그인 화면
3. 회원 가입
```
  + (Order)OAuth and then Phone No. Certification to upgrade grade
  + (Order)Email Registeration and then Phone No. Certification to upgrade grade
  + (Deliver) OAuth or Email Registeration. Phone No. Certification. ID Card Photo and Account No.  more info
  + 노출이름 등록
```
4. 홈화면
```
  + 공지내용
  + Order Request/Deliver Search 메뉴
  + 회원 가입정보 등록 상태에 따라 버튼 활성화 구분하면 어떨까?
```    
5. **Order**
```
  5.1 Order Request
    - 출발지 입력
      . 주소 검색
      . GPS 선택
      . 지도 선택
    - 목적지 입력
      . 주소 검색
      . 지도 선택
  5.2 배송물품 종류 선택 및 입력
      . 물품 수취 가능 시간 등록
      . 크기
      . 무게
      . 종류
      . 주의사항
      . 배송 물품 사진 업로딩
  5.3 결재
      . 예상 금액
      . 쿠폰
      . 카드
      . 계좌이체
  5.4 Order 목록 화면
    - 현재 등록된 Order(결제 대기, 결재 완료, 요청중)
    - 과거 등록한 Order(배송 완료)
  5.5 목록 선택시 상세 화면
    - Order 일시, 배송완료 예상 일시, 배송완료 일시, 확정 일시
    - 물품 정보, 비용, 배송자 아이디(노출이름)
    - **Order 선택한 Deliverer가 있으면 'N'표시, 여러명일 경우 리스트로 표시, 선택버튼 제공**
```
6. **Deliver**
```
  6.1 Order Search
    - 지역구 내
    - 광역지구
    - 출발지, 목적지 경로 내
  6.2 Order List(Search Result)
    - 리스트로 표시
    - 지도내 표시
  6.3 Order 배송 요청 선택
    - Order 요청자에게 Deliver 신청 전달
    - Multi
  6.4 선택목록 화면
    - 선택 리스트
      . 수락 완료
      . 수락 실패(다른 사람 선택됨)
      . Order 요청 취소
  6-5 목록 선택시 상세
    - 수락완료(배송필요)
      . 출발 버튼 - 예상 도착 시간 전달
      . 삭제 버튼 - 배송 취소 전달
      . 배송 출발 위치, 도착 위치, 배송 요청 시간, 비용, 물건 정보 등.
    - 수락 실패, Order 요청 취소
      . 삭제 버튼
    - 배송완료 요청
      . 확인 코드 입력
      . 사진 업로딩
```
7. To Do More
```
  > Deliverer 이동 스케쥴 사전 등록
  > Deliverer 할인 비율 등록
```
8. for Safe Deliver
```
  > 보험가입
  > Deliver 보증금 제도
    >> 보증금액에 맞추어 고객이 등록한 배송물품 가격 한도내 배송물품 노출(보증금은 향후 100% 환불)
```
