# 3# WEP 프로젝트

### 1.주제[온라인 Book 쇼핑몰]
--------------------------------------------------------------------
![메인화면](https://user-images.githubusercontent.com/69965049/111269702-4790d580-8672-11eb-92b1-ba8725077487.gif)
#### #설명:
기존의 대표 온라인 서점 플랫폼을 밴치마킹하여 쇼핑몰의 기본 구조와 데이터의 구조관계를 분석하고 JSP동작과 MVC 동작 패턴을 학습하여 CSS와 자바스크립트, 부트스트랩, Ajax를 응용한 JSP기반의 웹사이트 팀프로젝트입니다.
<br><br>


### 2.개발기간
-----------
![개발일정](https://user-images.githubusercontent.com/69965049/111098663-52bb0700-8587-11eb-96e1-dbedcd68c45d.png)
<br><br>


### 3.요구 분석 및 구현 업무
-----------
![요구사항 및 ](https://user-images.githubusercontent.com/69965049/111408402-9bee9080-8718-11eb-9bfe-6267dc20e282.png)
<br><br>


### 4.개발환경
-----------
![개발환경](https://user-images.githubusercontent.com/69965049/111098751-7bdb9780-8587-11eb-982a-e3b64ec3a102.png)
<br><br>


### 5.담당업무
-----------
![담당업무](https://user-images.githubusercontent.com/69965049/111408459-ac067000-8718-11eb-8492-ea8b17bcfb14.png)
<br><br>


### 6.ERD
-----------
![erd구조](https://user-images.githubusercontent.com/69965049/111252424-713b0400-8654-11eb-89ca-880c310dafb5.png)
![북적북적_최종_210222](https://user-images.githubusercontent.com/69965049/111053537-f0d7a000-84a7-11eb-8167-8e36ed36120a.png)
<br><br>


### 7.시연
-----------
 #### #1.[약관동의 및 이메일 인증]
![회원가입](https://user-images.githubusercontent.com/69965049/111057069-c4338080-84c7-11eb-80c8-d6763a463842.gif)
 #### #설명
 1. 약관보기: 클릭 시 모달을 사용하여 약관에 대한 상세보기 기능을 사용했습니다.
 2. E-mail인증: Gmail Smtp 설정을 통해 6자리의 랜덤 인증번호를 송신하고, Ajax를 응용한 전송 유무상태를 확인할 수 있습니다.
 <br><br>
 #### #1-2 [인증 메일 수신]
![이메일 인증](https://user-images.githubusercontent.com/69965049/111057412-b29fa800-84ca-11eb-90f3-b1e1e2c68a17.png)
#### #설명
1. 수신받은 인증메일

-----------
#### #2.[회원가입]
![회원가입_2](https://user-images.githubusercontent.com/69965049/111057708-ebd91780-84cc-11eb-8227-291d4b737e4e.gif)
#### #설명
1. 아이디 중복검사: Ajax를 응용한 아이디 중복 유무상태를 확인할 수 있습니다.
2. 주소 API: Daum 우편번호 서비스를 이용해 쉽고 간편하게 우편번호 검색, 도로명 주소 입력 기능을 이용할 수 있습니다.
<br><br>

#### #2-2 [주소 API]
![주소 API](https://user-images.githubusercontent.com/69965049/111057619-3ad27d00-84cc-11eb-8421-f031ed554321.png)
#### #설명
1. 주소 API입니다.
<br><br>
-----------
#### #3.[아이디&비밀번호 찾기]
![아디비번찾기](https://user-images.githubusercontent.com/69965049/111058125-a2d69280-84cf-11eb-9c71-297ca9a39d8c.gif)
1. 아이디 찾기: 이름과 [전화번호, 이메일, 주민번호]를 이용하여 해당 아이디를 확인할 수 있습니다.
2. 비밀번호 찾기: 이름과 아이디와 [전화번호, 이메일, 주민번호]릉 이용하여 해당 비밀번호를 확인할 수 있습니다.
<br><br>
-----------
#### #4.[로그인]
![로그인](https://user-images.githubusercontent.com/69965049/111331779-94959b80-86b4-11eb-8c96-76424d8fa810.gif)
#### #설명
1. 회원 로그인 페이지입니다.
2. 아이디 TEST001~TEST050까지는 휴면계정입니다. 휴면계정 로그인 시 "Dormency ID"를 확인할 수 있습니다.
3. 일반계정 로그인 시 잘못된 정보를 기입하면 "Login Failed"를 확인할 수 있습니다.
<br><br>

#### #4-2.[소셜 로그인]
![소셜로그인 카카오](https://user-images.githubusercontent.com/69965049/111280824-9d1faf00-867f-11eb-8d8f-9c922534aff1.gif)
#### #설명
1. 카카오 로그인 API입니다.
<br><br>

-----------
#### #5.[회원정보 조회&수정]
![회원정보 수정](https://user-images.githubusercontent.com/69965049/111343390-b8f67580-86be-11eb-8a50-0451c2633f6d.gif)
#### #설명
1. 회원정보 수정 페이지입니다.
<br><br>

#### #5-2[비밀번호 수정]
![비밀번호 수정](https://user-images.githubusercontent.com/69965049/111343276-9e240100-86be-11eb-8bff-09975ed27b01.gif)
#### #설명
1. 변경할 비밀번호와 재확인 비밀번호가 불일치 시 "암호가 일치하지 않습니다"를 확인할 수 있습니다.
2. 현재 비밀번호가 불일치 시 "현재 비밀번호가 틀렸습니다"를 확인할 수 있습니다.
<br><br>

#### #5-3[회원탈퇴]
![회원탈퇴](https://user-images.githubusercontent.com/69965049/111346142-46d36000-86c1-11eb-904b-5f20401639fd.gif)
#### #설명
1. 회원탈퇴 페이지입니다.
2. 정상 비밀번호 입력 시 행당 계정의 Session을 초귀화하고 계정을 Delete 시킨 후 메인페이지로 이동합니다.
<br><br>

-----------
#### #6.[회원계정 관리]
![고객 계정관리](https://user-images.githubusercontent.com/69965049/111269786-5e372c80-8672-11eb-87a6-f3ae18314516.gif)
#### #설명
1. 관리자가 회원계정을 관리하기 위한 페이지 입니다.
2. 특정 회원계정을 탈퇴시킬 수 있습니다.
3. 특정 회원계정을 휴면계정으로 전환시킬 수 있습니다.
4. 특정 회원계정 상세정보를 조회할 수 있습니다. 
5. 페이지당 회원리스트 개수(20, 40, 50)를 조절할 수 있습니다. 
<br><br>

-----------

#### #7.[휴면계정 관리]
![휴면 계정관리](https://user-images.githubusercontent.com/69965049/111275677-c0476000-8679-11eb-85b4-cd902ec29c4b.gif)
#### #설명
1. 관리자가 휴면계정을 관리하기 위한 페이지 입니다.
2. 특정 휴면계정을 탈퇴시킬수 있습니다.
3. 특정 휴면계정을 일반계정으로 전환시킬 수 있습니다.
4. 특정 휴면계정 상세정보를 조회할 수 있습니다.
5. 페이지당 휴면리스트 개수(10, 20, 30)를 조절할 수 있습니다.
<br><br>

-----------
#### #8.[리스트 페이징]
![휴면페이징](https://user-images.githubusercontent.com/69965049/111275680-c2112380-8679-11eb-9936-1e2cfdde2cc9.gif)
#### #설명
1. 페이징 기능입니다.
<br><br>
-----------
#### #9.[후기]
![후기](https://user-images.githubusercontent.com/69965049/111409387-34394500-871a-11eb-8c91-aa1e342c27a9.png)
