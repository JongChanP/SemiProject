FORK된 해당 프로젝트는 국비지원 교육시 Semi Project로 진행한 작업물 입니다. 😃 
Semi Project는 웹페이지 제작의 전체적인 과정을 직접 겪어보기 위한 Project 입니다. 

팀원들의 작업물이 전체로 올라와 있어
1. 프로젝트 전체 설명
2. 제가 작업한 작업물 경로와 설명
을 해보도록 하겠습니다.

&nbsp;

## 1. 어떤 프로젝트 인가? 
Semi Project 진행 당시 여러 파트가 많은 웹 페이지를 만들고 싶어
**준오헤어** 사이트를 모방하여 헤어샵 웹 페이지를 만들었습니다.

&nbsp;

저희 팀은 모든 팀원들이 비전공자로
각자 원하는 파트를 맡아 작업을 하였습니다.

&nbsp;

## 2-1. 나의 작업은?
저는 당시 개발실력이 뛰어난 편은 아니었지만
해보지 않은 것에 도전해보고 싶은 마음이 커서
**상품과 관련된 화면 구현과 기능**을 담당하였습니다.

&nbsp;

## 2-2. 개발 환경 / 기술 스택은?
**개발환경**

- Eclipse
- Apache Tomcat 9.0
- jsp
- Visual Studio Code

**기술 스택**

- Java(jdk 1.8.0)
- Oracle DB
- vanila javascript
- jQuery
- HTML5
- CSS

&nbsp;

## 2-3. 나의 작업 파일 경로
**Eclipse**
상품 (Product)
- ListController : https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/src/coty/market/controller/list
- DetailController : https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/src/coty/market/controller/detail
- service : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/market/service/ProductService.java
- dao : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/market/dao/ProductDao.java
- vo : https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/src/coty/market/vo

장바구니 (Cart)
- Controller : <br />
장바구니 추가
https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/CartAddController.java
<br />
장바구니 조회
https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/CartController.java
<br />
장바구니 삭제
https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/CartDeleteController.java
- service : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/service/CartService.java
- dao : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/dao/CartDao.java
- vo : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/vo/CartVo.java

주문 목록 
- Controller : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/OrderListController.java
- service : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/service/OrderService.java
- dao : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/dao/OrderDao.java
- vo : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/vo/OrderVo.java

디자이너
- Controller : 
근무표 조회 
https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/designer/controller/D_calendarController.java
예약목록 조회
https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/designer/controller/D_rv_chartController.java



**jsp**
상품
- https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/webapp/WEB-INF/views/market
상품 상세
- https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/webapp/WEB-INF/views/market/detail
장바구니
- https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/member/Cart.jsp
주문 목록
- https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/member/orderList.jsp
디자이너 예약목록
- https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/designer/d_rv_chart.jsp
근무표
- https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/designer/d_calendar.jsp

&nbsp;

## 2-4. 완성된 화면
<details>
  <summary>상품 List 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/ProductList.png" />
  </div>
</details>
<details>
  <summary>상품 Detail 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/ProductDetail1.png" />
  </div>
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/ProductDetail2.png" />
  </div>
</details>
<details>
  <summary>디자이너 근무표 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/DesignerCalender.png" />
  </div>
</details>
<details>
  <summary>디자이너 예약 확인 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/Designer.png" />
  </div>
</details>
<details>
  <summary>장바구니 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/Cart.png" />
  </div>
</details>
<details>
  <summary>회원 주문 목록 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/SemiProject/blob/main/SemiImage/CustomerOrder.png" />
  </div>
</details>

