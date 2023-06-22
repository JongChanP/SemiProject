# KH정보교육원 Semi Project 😃
Semi Project는 웹페이지 제작의 전체적인 과정을 직접 겪어보기 위한 Project 입니다. 
처음 진행해본 Project로 기초적인 CRUD에 중점을 두고 작업하였습니다. 봐주셔서 감사합니다 !

&nbsp;

## 목차
### ​1️⃣ 어떤 프로젝트 인가? 
### 2️⃣ 나의 작업은?
### 3️⃣ 개발 환경 / 기술 스택은?
### 4️⃣​ 나의 작업 파일 경로
### 5️⃣ 완성된 화면
### 6️⃣ 소감

&nbsp;

## ​1️⃣ 어떤 프로젝트 인가?  
Semi Project 진행 당시 여러 파트가 많은 웹 페이지를 만들고 싶어
**준오헤어** 사이트를 모방하여 헤어샵 웹 페이지를 만들었습니다.

&nbsp;

저희 팀은 모든 팀원들이 비전공자로
각자 원하는 파트를 맡아 작업을 하였습니다.

&nbsp;

## 2️⃣ 나의 작업은?
저는 당시 개발실력이 뛰어난 편은 아니었지만
해보지 않은 것에 도전해보고 싶은 마음이 커서
**상품과 관련된 화면 구현과 기능**을 담당하였습니다.

&nbsp;

## 3️⃣ 개발 환경 / 기술 스택은?
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

## 4️⃣​ 나의 작업 파일 경로
**Eclipse**
<details>
  <summary>상품 (Product)</summary>
  <br />
  <div markdown="1">
    - ListController : https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/src/coty/market/controller/list
    - DetailController : https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/src/coty/market/controller/detail
    - service : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/market/service/ProductService.java
    - dao : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/market/dao/ProductDao.java
    - vo : https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/src/coty/market/vo
  </div>
</details>

<details>
  <summary>장바구니 (Cart)</summary>
  <br />
  <div markdown="1">
    - Controller : 
    - 장바구니 추가
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/CartAddController.java
    - 장바구니 조회
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/CartController.java
    - 장바구니 삭제
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/CartDeleteController.java
    - service : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/service/CartService.java
    - dao : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/dao/CartDao.java
    - vo : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/vo/CartVo.java
  </div>
</details>

<details>
  <summary>주문 목록 </summary>
  <br />
  <div markdown="1">
    - Controller : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/controller/OrderListController.java
    - service : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/service/OrderService.java
    - dao : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/dao/OrderDao.java
    - vo : https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/member/vo/OrderVo.java
  </div>
</details>

<details>
  <summary>디자이너</summary>
  <br />
  <div markdown="1">
    - Controller : 
    - 근무표 조회 
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/designer/controller/D_calendarController.java
    - 예약목록 조회
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/src/coty/designer/controller/D_rv_chartController.java
  </div>
</details>

**jsp**

<details>
  <summary>디자이너</summary>
  <br />
  <div markdown="1">
    - 상품
    https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/webapp/WEB-INF/views/market
    - 상품 상세
    https://github.com/JongChanP/SemiProject/tree/main/workspace/semiPrj/webapp/WEB-INF/views/market/detail
    - 장바구니
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/member/Cart.jsp
    - 주문 목록
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/member/orderList.jsp
    - 디자이너 예약목록
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/designer/d_rv_chart.jsp
    - 근무표
    https://github.com/JongChanP/SemiProject/blob/main/workspace/semiPrj/webapp/WEB-INF/views/designer/d_calendar.jsp
  </div>
</details>

&nbsp;

## 5️⃣ 완성된 화면
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

## 6️⃣ 소감
Semi Project를 처음 시작할 당시 스스로 작업을 해보는게 익숙치 않아 많은 어려움이 생겼음에도 스스로 해결해보는 능력과
어떤 부분에선 무엇이 불편한지 또 코드를 치며 어떤 부분을 개선해야되는지 알게 되는 Project 였던 것 같습니다.
결과에 대해선 구현하지 못한 것들이 있어 아쉬움이 남지만 좋은 팀원과 함께하고 과정을 배웠다는 거에 크게 만족했습니다.

