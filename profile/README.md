# 부각콩 (Boogakcong)

![image](https://github.com/user-attachments/assets/baf07699-8971-4f81-bf2c-a883c9f97d06)

<p align="center">부산대학교 학생들을 위한 카페 정보 제공 플랫폼 "부각콩"입니다.</p>
<p align="center">
    부산대 학생들이 각자 코딩하고 공부할 수 있는 카페 정보를 제공하고, 카페 소유자와 사용자가 상호작용할 수 있도록 돕는 플랫폼입니다.
</p>

<details>
<summary>📑 목차</summary>

- [📌 프로젝트 소개](#프로젝트-소개)
- [📸 프로젝트 주요 화면](#프로젝트-주요-화면)
- [🛠️ 기술 스택](#기술-스택)
    - [Frontend](#Frontend)
    - [Backend](#Backend)
- [📄 API 명세서](#API-명세서)
- [📊 ERD](#ERD)
- [🚀 프로젝트 실행 방법](#프로젝트-실행-방법)
- [🔒 보안 설정](#보안-설정)
- [👥 기여자](#기여자)

</details>

## 📌 프로젝트 소개

부각콩은 부산대학교 학생들을 위한 카페 정보 제공 플랫폼입니다. 사용자는 카페의 위치, 시설 정보(와이파이, 콘센트, 테이블 등)와 도보 이동 시간을 확인할 수 있습니다. 또한, 카페 소유자는 자신의 카페를 등록하고 관리할 수 있으며, 커뮤니티 매니저와 상호작용하며 다양한 기능을 제공합니다.

**주요 기능**

1. **카페 정보 제공** : 카페의 위치, 시설, 도보 시간 등의 정보를 제공하여 학생들이 효율적으로 공부할 수 있는 장소를 찾을 수 있도록 돕습니다.
2. **카페 소유자 관리** : 카페 소유자는 공지사항 업데이트 및 카페 정보 수정 기능을 통해 자신의 카페를 관리할 수 있습니다.
3. **리뷰 기능** : 사용자는 카페에 대한 후기를 작성하고 다른 사람들의 후기를 확인할 수 있습니다.

## 🛠️ 기술 스택

### Frontend
- **Next.js v15.0.4** 
- **TypeScript v5.7.2**
- **MUI (Material UI)**
- **Jotai**

### Backend
- **Java 17** 
- **Spring Boot v3.4.0**
- **Gradle 7.5 이상**
- **Spring Security & JWT** 
- **Spring Data JPA** 
- **PostgreSQL** 
- **AWS S3** 

## 📸 프로젝트 주요 화면

**⚠️ 모든 페이지는 아이폰 X12 해상도에 최적화되어 있습니다. 개발자 모드에서 해당 기기 해상도로 확인하시는 것을 권장합니다.**

---

### 로그인 및 회원가입
<div align="center">
<table>
  <tr>
    <td align="center" width="300px">
      <strong>로그인 페이지</strong><br>
      <img src="https://github.com/user-attachments/assets/9289c2a1-d17e-4cd5-a7d5-37d32cc13e69" width="300px" alt="로그인 페이지" />
    </td>
    <td align="center" width="300px">
      <strong>회원가입 페이지</strong><br>
      <img src="https://github.com/user-attachments/assets/03db80ed-623e-46f4-bb02-995518dddcbd" width="300px" alt="회원가입 페이지" />
    </td>
  </tr>
</table>
</div>

---

### 카페
<div align="center">
<table>
  <tr>
    <td align="center" width="300px">
      <strong>카페 리스트 조회</strong><br>
      <img src="https://github.com/user-attachments/assets/ae90b1fb-ead4-4656-a350-c986c96b5837" width="300px" alt="카페 리스트 조회" />
    </td>
    <td align="center" width="300px">
      <strong>카페 단건 조회</strong><br>
      <img src="https://github.com/user-attachments/assets/34d1f8aa-02e0-4885-87e6-8c07beba44c2" width="300px" alt="카페 단건 조회" />
    </td>
  </tr>
</table>
</div>

---

### 게시판
<div align="center">
<table>
  <tr>
    <td align="center" width="300px">
      <strong>게시판 리스트 조회</strong><br>
      <img src="https://github.com/user-attachments/assets/6825f10b-9fa7-456b-9c9c-ea690ec595be" width="300px" alt="게시판 리스트 조회" />
    </td>
    <td align="center" width="300px">
      <strong>게시판 글 단건 조회</strong><br>
      <img src="https://github.com/user-attachments/assets/9b824634-6e28-42ce-9c76-fb97e3dedf90" width="300px" alt="게시판 글 단건 조회" />
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <strong>게시글 작성</strong><br>
      <img src="https://github.com/user-attachments/assets/275c7a4f-3557-4510-aa2c-5f5ac8fcef1a" width="300px" alt="게시글 작성" />
    </td>
  </tr>
</table>
</div>

---

### 마이페이지
<div align="center">
<table>
  <tr>
    <td align="center" width="300px">
      <strong>마이페이지 메인</strong><br>
      <img src="https://github.com/user-attachments/assets/f3675f60-9dd8-418a-a30c-2a64a7531b3a" width="300px" alt="마이페이지 메인" />
    </td>
    <td align="center" width="300px">
      <strong>내 카페 등록</strong><br>
      <img src="https://github.com/user-attachments/assets/cea4e260-4476-40a5-9444-a3c9055be912" width="300px" alt="내 카페 등록" />
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <strong>내 카페 관리</strong><br>
      <img src="https://github.com/user-attachments/assets/39b5de79-5d02-4e6f-96a2-6d664436efe7" width="300px" alt="내 카페 관리" />
    </td>
  </tr>
</table>
</div>

---

### 커뮤니티 관리자
<div align="center">
<table>
  <tr>
    <td align="center" width="900px">
      <strong>커뮤니티 관리자 콘솔</strong><br>
      <img src="https://github.com/user-attachments/assets/ebeb0d57-7fd0-4a31-a16d-dada38a009ab" width="900px" alt="커뮤니티 관리자 콘솔" />
    </td>
  </tr>
</table>
</div>

---

### 운영 관리자
<div align="center">
<table>
  <tr>
    <td align="center" width="900px">
      <strong>운영 관리자 콘솔</strong><br>
      <img src="https://github.com/user-attachments/assets/3b2a4464-fd25-4ac7-adc7-73f824cc5172" width="900px" alt="운영 관리자 콘솔" />
    </td>
  </tr>
</table>
</div>





## 📄 API 명세서
[API 명세서](https://bubble-pick-143.notion.site/API-15641de2210c80f3a1c6cf678f8129a6)

## 📊 ERD
![스크린샷 2024-12-08 오후 6 36 22](https://github.com/user-attachments/assets/0bce5f1f-c387-4cc2-bf1c-6045cd425056)


## 🚀 프로젝트 실행 방법
### FrontEnd
```
git clone https://github.com/ZoJim/Boogakcong-FE.git
```

``` 
yarn install
yarn dev
```

### Backend

`/resources/application.yml`에 키값 정보를 채우고, PostgreSQL의 host, password를 알맞게 설정합니다.

설정된 프로그램 기준
```
url: jdbc:postgresql://localhost:5432/postgres
username: postgres
password: 123456
```

```
git clone https://github.com/ZoJim/Boogakcong-BE.git
```

```
./gradlew build
./gradlew bootRun
```

## 🔒 보안 설정
Boogakcong은 Spring Security와 JWT를 사용하여 인증 및 권한 관리를 제공합니다. 백엔드는 JWT로 사용자 인증을 처리하며, 프론트엔드는 Jotai와 LocalStorage를 활용하여 사용자 상태를 관리합니다. 또한, CORS 정책을 통해 안전한 API 접근을 보장하며, 민감한 설정 값은 환경 변수로 관리됩니다.


## 👥 기여자

<div align="center">
<table align="center">
  <tr>
    <td align="center" width="200px">
      <a href="https://github.com/stopmin" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/108014449?v=4" width="100px" alt="정지민 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/suyoungee" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/105601298?v=4" width="100px" alt="조수영 프로필" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/stopmin" target="_blank">정지민</a>
    </td>
    <td align="center">
      <a href="https://github.com/suyoungee" target="_blank">조수영</a>
    </td>
  </tr>
</table>
</div>
