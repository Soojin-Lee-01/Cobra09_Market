# 💻 **Cobra09**

> 누구나 공동구매의 주선자가 될 수 있고, 구매자가 될 수 있도록 공동구매 웹 플랫폼을 개발했습니다.

---

## 1️⃣ **소개**

**Cobra09_Market**는 간편하게 공동구매를 등록하고 판매를 신청할 수 있는 플랫폼입니다.  

## 2️⃣ **팀원 소개**

| 이름   | 역할         | GitHub                   | 
| ------ | ------------ | ------------------------ |
| 최원정 | 팀장, 풀스택 | [github.com/CWJ1222](#)  |
| 이수진 | 백엔드       | [github.com/younghee](#) | 
| 오성환 | 백엔드       | [github.com/gogigogigogi](#)   |
| 최수연 | 프론트엔드   | [github.com/suyeon-dev](#)    |
| 오태원 | 프론트엔드   | [github.com/oh2815](#)     | 

---

## 3️⃣ **기능**

- 사용자 회원가입 및 로그인
- 공동구매 판매 신청 및 구매 신청
- 정보 수정 및 조회
- 공동 구매 내역 조회
- 댓글 및 찜하기

### 주요기능
| 홈 화면 |
|:---:|
|![홈 화면](https://github.com/user-attachments/assets/c7f97bc1-87a5-49cc-b622-76c31937fb34) |
#### 메인 페이지에는 카테고리 ID를 이용해 구분하여 볼 수 있게 구성했습니다. 또한 wishlists 테이블을 통해 찜을 합산하여 찜이 많은 순으로 정렬했습니다.
| 회원가입/로그인 |
|:---:|
| ![회원가입/로그인](https://github.com/user-attachments/assets/4475ff41-e427-4ff0-a35b-5817bd2ed4e0) |
#### OAuth 프로토콜을 이용한 카카오 로그인와 이메일 기반 일반 로그인 구현했습니다. 
| 상품 판매 |
|:---:|
| ![상품 판매](https://github.com/user-attachments/assets/22b0f63a-db76-4b73-8e2d-8e039146523e) |
#### product 테이블에 공동 구매 주선 물품을 등록하도록 했습니다.
| 마이페이지 |
|:---:|
| ![마이페이지](https://github.com/user-attachments/assets/6d98e535-7db6-4251-90d2-099da1a81ecc) |
#### user 테이블을 이용해 정보 수정이 가능하도록 구현했습니다. 또한 product와 user을 조인하여 내가 주선한 물품을 보여주고 product와 order_list, user을 중첩 조인하여 내가 구매한 상품을 조회할 수 있습니다. 마지막으로 wishlist를 통해 내가 찜한 정보를 조회할 수 있습니다.
| 찜하기 |
|:---:|
| ![찜하기](https://github.com/user-attachments/assets/99f65a8f-115a-4e16-bd4a-e541bc655c6d) |
#### 물품을 찜하거나 찜한 것을 취소할 수 있습니다. 테이블에 데이터가 존재하면 데이터를 삭제하여 찜을 취소 처리하고, 데이터가 존재하지 않으면 데이터를 삽입해 찜 처리를 했습니다.
| 댓글 달기 |
|:---:|
| ![댓글달기](https://github.com/user-attachments/assets/81e78d35-a719-46f1-abb6-dffe9f5ac8d9) |
#### comment 테이블을 따로 구성하여 댓글 달기를 구현했습니다. 또한 대댓글 기능도 가능합니다.

---

## 4️⃣ **개발기간**
2024-12-11 ~ 2024-12-30

---

## 5️⃣ **기술 스택**

- **프론트엔드:** EJS, HTML/CSS, JavaScript  
- **백엔드:** Node.js, Express.js, Sequelize  
- **데이터베이스:** MySQL
- **기타:** Axios, Multer, OAuth  

---

## 6️⃣ **ERD**

![제목을-입력해주세요_-001 (8)](https://github.com/user-attachments/assets/12c79867-a6b0-4125-8479-c48bda618e7e)

---

## 7️⃣ **개인회고**
### 🙋‍♀️ 내가 맡은 역할
#### - DB & API 설계
#### - 찜기능
#### - 마이페이지(내 정보 수정/조회, 구매/판매 내역 확인, 찜한 내역 확인)
### ⚽ 트러블 슈팅
#### - 외래키
#### - 중복조인
#### - ERD 식별관계/비식별관계
