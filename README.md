구글 OTP (TOTP)를 적용하기 위한 샘플 작업

1. 프로젝트를 생성하며, 아래의 라이브러리를 추가한다.

 dependencies {
	compile("org.springframework.boot:spring-boot-starter-data-jpa")
	compile("org.springframework.boot:spring-boot-starter-security")
	compile("org.springframework.boot:spring-boot-starter-web")
	compile("org.springframework.boot:spring-boot-starter-mail")
	compile("org.thymeleaf:thymeleaf")
	compile("org.thymeleaf:thymeleaf-spring5")
	annotationProcessor("org.projectlombok:lombok")
	compile("org.projectlombok:lombok")
	compile("com.warrenstrange:googleauth:0.5.0")
	runtime("com.h2database:h2")
	testCompile("org.springframework.boot:spring-boot-starter-test")
 }

<참고>

위의 디펜던시 중 spring5와 googleauth 는 별도로 mavenrepository 에서 구해온다.
(spring starter에서 검색 안됨)

2. 기본 프로젝트만 생성 후 http://localhost:8080 을 치면 기본 로그인 창이 나온다.
 - 여기에 resources/templates 및에 성공시 보여줄 index.html 만들자.
 - 서비스 구동시 콘솔에 보여주는 Using generated security password : 값을 카피해둔다. 사용자명은 user이다.
 
 <Google Authenticator TOTP>
 - https://java.ihoney.pe.kr/449
 - https://github.com/ihoneymon/spring-security-2step-verification
 - https://github.com/wstrange/GoogleAuth
 - https://www.baeldung.com/spring-security-two-factor-authentication-with-soft-token
 - https://zero-gravity.tistory.com/221
 
 
 <Apache Camel>
 - https://camel.apache.org/manual/latest/setBody-eip.html
 - https://github.com/hinunbi/eip-practice
 - https://github.com/apache/camel
 - https://www.baeldung.com/apache-camel-spring-boot
 
 <br>
 텍스트 아이콘 제작 사이트
 
 http://patorjk.com/software/taag/#p=display&f=Slant&t=abc
 
 
 
