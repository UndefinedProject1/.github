## 📖 Project Title / All Gaincs
![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=All%20Ganics&fontSize=90)
> All Ganics은 점점 심해지는 지구 온난화에 따라 사람들이 좀 더 쉽게 착한 소비를 할 수 있도록 친환경, 제로웨이스트, 리사이클링 제품들을 모아놓은 쇼핑몰입니다.
> 
> 친환경 제품을 구매하려고해도 소비자가 많은 정보를 알아보고 구매해야한다는 불편함이 있었습니다. 그래서 저희 팀원들은 지그재그, 브랜디와 같이 친환경제품 하면 들어가서 손쉽고 간편하게 구매할 수 있는 사이트를 제작하고자하여 이번 프로젝트를 만들게 되었습니다. 

👉 [PPT로 보고싶으신 분](https://prezi.com/view/Fxg2Ah7phHw4t6tkQpKC/)

## 📝 Process 과정

* 전체 프로젝트 기간 : 2021.10.04 ~ 2021.12.03

* 세부 프로젝트 진행과정


| 기간| 내용 |  
| ------ | ------ |
| 2021.10.03 ~ 04 | 아이디어 미팅 - 주제 선택 |
| 2021.10.05 ~ 11 | 요구사항 분석 및 ERD 설계 |
| 2021.10.12 ~ 25  | 프로젝트 구체화 - 브랜드 최종 선별 및 사이트 UI, UX 디자인 |
| Product_table | 아이콘을 이용한 장바구니 기능, pagination  |
| Product_detail_page | 상품정보, 상세이미지, 후기작성 및 목록(신고기능), 문의작성 및 목록, 교환 환불정보 |
| My_Page (회원) | 기본 회원정보 수정(Daum 우편 번호 API사용), 주문 및 교환환불 내역, 문의내역 |
| Product_Cart (회원) | 기본 팝업 형식에서 장바구니 페이지로 이동, 수령 변경 후 저장 |
| Order_Page (회원) | 성명, 연락처, 주소 필수 기입(유효성), PG 결제 연동 API 사용, 환불 교환 정책 모달처리 |

## 🚀 Getting Started / 어떻게 시작하나요?


### Prerequisites / 선행 조건

아래 사항들이 설치가 되어있어야합니다.

```
예시
```

### Guide / 가이드

All-Ganic 프로젝트의 많은 기능들을 더 쉽고 간편하게 아래의 가이드를 통해 즐길수있습니다.

저희 All_Ganics 는 회원가입의 과정 없이 사이트를 둘러보는 것은 가능하나 일부 기능(장바구니, 주문, 마이페이지)은 회원 한정으로 제작되어있습니다. 회원가입(일반, 카카오톡)을 이용해보시는 방법도 있으나 하단의 대표 아이디로 로그인하셔서 사이트를 이용해보실 수 있습니다.

관리자 페이지(admin_page)를 이용하시려면 관리자 아이디로 로그인 하셔야합니다. 


```
- 멤버
아이디 : guest@gmail.com
암호 : guest123!

- 관리자
아이디 : a@gmail.com 
암호 : aa
```

저희 올가닉스는 신고 및 매출 현황을 socket을 이용하여 관리자 페이지에 실시간으로 업데이트 되도록 구성되어있습니다. 각각 관리자와 멤버로 동시에 로그인한 후 이용하시길 추천드립니다. 

## 💁 Built With / 누구랑 만들었나요?

| 기간| 내용 |  
| ------ | ------ |
| [정지희](https://github.com/Insa14) | Back-end |
| [권다은](https://github.com/kaydan95) | Front-end |
| [정다경](https://github.com/Jeong-Dagyeong) | Front-end |

 
## Running the tests / 테스트의 실행

어떻게 테스트가 이 시스템에서 돌아가는지에 대한 설명을 합니다

### 테스트는 이런 식으로 동작합니다

왜 이렇게 동작하는지, 설명합니다

```
예시
```

### 테스트는 이런 식으로 작성하시면 됩니다

```
예시
```

## Deployment / 배포
🔗 : http://18.223.251.77:3000/

/admin_page와 /페이지 두 개를 여시고 결제나 리뷰를 적었을 때 실시간으로 관리자페이지에 어떻게 나타나는지 확인해보시는 것을 추천드립니다.
## 🛠 Tech Stack / 기술스택
- ![Vue JS](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white) : 프론트엔드 메인 개발 환경
- ![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=Java&logoColor=white) : 백엔드 메인 개발 환경
- ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=Spring%20Boot&logoColor=white) : 프레임워크
- ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=Node.js&logoColor=white) : 실시간 데이터처리를 위한 서버


## Acknowledgments / 감사의 말

* 그동안 개발을 알려주신 선생님들께 너무 감사드립니다. 덕분에 한 명의 멋진 개발자로 성장하는 발판을 단단하게 쌓을 수 있었습니다.
* 실제 쇼핑몰을 투자 받아 출시할 것처럼 진지하게 해보자는 저의 말에 같이 불타올라 유저들에게 어떻게 보기에 편안한지 계속 고민하고 디자인도 이쁘게 하기위해 각종 포스터, 사이트들을 찾아보고 연구한 우리 프론트엔드 팀원분들께 찬양의 말을 보냅니다.   

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
