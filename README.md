# Self introduction homepage

One Paragraph of project description goes here

## Getting Started

Run on Server the index.jsp file 

### Development environment

JDK 설치(ver 1.8)
이클립스 설치
tomcat 설치(ver 8.5)


### Development order

1. 프로젝트 이름을 aboutme 로 Dynamic Web Project 를 생성합니다.
2. 생성된 aboutme 프로젝트의 webContent 폴더에 index.html, aboutme.html, photo.html 파일을 작성합니다.
3. 이미 다른곳에서 작성했다면 해당 디렉토리로 이동합니다. 주의) 반드시 이클립스에서 붙여넣기 합니다.
4. 서블릿 클래스의 이름은 TodayServlet으로 하고, 해당 서블릿의 URL경로는 http://localhost:8080/aboutme/today 로 하는 서블릿 클래스를 생성합니다.
5. 기획서의 내용에 맞게 화면에 현재시간과 메인화면 링크가 나오도록 페이지를 작성합니다.

### Main Process
1. html 간에 이동은 <a> 태그를 사용해서 html 이동
2. 몇시에요 버튼을 클릭시 form 태그를 통해서 jsp 페이지 이동 method가 post이므로 doPost 메소드 구현
  
