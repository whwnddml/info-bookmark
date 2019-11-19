���� OTP (TOTP)�� �����ϱ� ���� ���� �۾�

1. ������Ʈ�� �����ϸ�, �Ʒ��� ���̺귯���� �߰��Ѵ�.

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

<����>

���� ������� �� spring5�� googleauth �� ������ mavenrepository ���� ���ؿ´�.
(spring starter���� �˻� �ȵ�)

2. �⺻ ������Ʈ�� ���� �� http://localhost:8080 �� ġ�� �⺻ �α��� â�� ���´�.
 - ���⿡ resources/templates �׿� ������ ������ index.html ������.
 - ���� ������ �ֿܼ� �����ִ� Using generated security password : ���� ī���صд�. ����ڸ��� user�̴�.
 
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
 