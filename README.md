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
 
 