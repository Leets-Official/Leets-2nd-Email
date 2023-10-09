![Imgur](https://i.imgur.com/38mBqej.png)

<br/>

# :one: Leets 2기 모집 Email Form

<br/>

동아리 Leets의 2기 모집 서류, 면접 결과 공지를 위한 email form 코드입니다.  
<br/><br/>

# :two: 프로젝트 진행 이유

<br/>

동아리 **Leets 2기**의 모집 결과를 메일로 자동화 하여 공지하기 위해 진행하게 되었습니다.

Leets만의 이메일 디자인을 사용하여 동아리 특색을 살리기 위한 목적도 있습니다.

Back End에 저장된 지원자들의 정보를 자동으로 배당하여 편하게 메일을 보내고자 하였습니다.  
<br/><br/>

# :three: 프로젝트 설명

<br/>

**Spring Boot**에서 **thymeleaf** 문법을 활용해, **html**로 구성된 이메일을 전송하는 프로그램입니다.

**th:class**와 **삼항 연산자**를 활용하여 동적 class명 할당을 통해 email form의 색상을 랜덤(🔵blue, :green_circle:mint, :yellow_circle:yellow)으로 전송하였습니다.

이름, 면접 날짜, 장소 등의 정보도 thymeleaf 문법을 사용하여 email form에 동적으로 할당하여 해야 할 일을 최소화 하고자 하였습니다.

Spring Boot에서 Leets 2기 홈페이지에서 전달 받은 지원자들의 정보를 바탕으로 메일을 보내게 되고, 서류 합격자들의 면접 참여 여부를 관리자 페이지에서 자동으로 확인 할 수 있게 구현 되었습니다.

_( 현재 이 레포지토리에는 Spring Boot 코드는 포함되어 있지 않고, email form, 즉 디자인 요소만 작성된 코드입니다. )_  
<br/>

서류 합격, 서류 불합격, 최종 합격, 최종 불합격, 추가 모집에 대한 공지 메일까지 총 5개의 email form이 작성 되어 있습니다.  
<br/><br/>

# :four: 미리보기

<br/>

1. **서류 합격**  
   <br/>

   <img src="https://i.imgur.com/ydRmUPX.png" width="360px" />
   <br/><br/>

2. **서류 불합격**  
   <br/>

   <img src="https://i.imgur.com/iMcMaZr.png" width="360px" />
   <br/><br/>

3. **최종 합격**
   <br/>

   <img src="https://i.imgur.com/UoXhh0m.png" width="360px" height="1100px"/>  
    <br/><br/>

4. **최종 불합격**
   <br/>

   <img src="https://i.imgur.com/JGUeP92.png" width="360px" height="1100px"/>  
    <br/><br/>

5. **추가 모집 공지**
   <br/>

   <img src="https://i.imgur.com/iTpVU8F.png" width="360px" />
   <br/><br/>
