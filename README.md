# \#tokyo🗼

# 

# \#20250911

#### 1번

package day1;



import java.util.Scanner;



public class Number2 {



&nbsp;	public static void main(String\[] args) {

&nbsp;		



&nbsp;		System.out.println("비밀번호를 입력하세요.");

&nbsp;		String password = "qwer1234";

&nbsp;		String result;

&nbsp;		

&nbsp;		if(password.equals("qwer1234")) {

&nbsp;			result = "비밀번호가 맞아요!";

&nbsp;		}else {

&nbsp;			result = "비밀번호가 틀렸어요!";

&nbsp;		}

&nbsp;		

&nbsp;		System.out.println(result);

&nbsp;		

&nbsp;		

&nbsp;	}



}

#### 2번

&nbsp;package day1;



import java.util.Scanner;



public class Number1 {



&nbsp;	public static void main(String\[] args) {

&nbsp;	

&nbsp;		Scanner sc = new Scanner(System.in);

&nbsp;		

&nbsp;		System.out.println("비밀번호를 입력하세요.");

&nbsp;		String password = sc.nextLine();

&nbsp;		String result;

&nbsp;		

&nbsp;		if(password.equals("qwer1234")) {

&nbsp;			result = "비밀번호가 맞아요!";

&nbsp;		}else {

&nbsp;			result = "비밀번호가 틀렸어요!";

&nbsp;		}

&nbsp;		

&nbsp;		System.out.println(result);

&nbsp;		

&nbsp;		sc.close();



&nbsp;	}



}



#### 3번

package day1;



public class Number3 {



&nbsp;	public static void main(String\[] args) {

&nbsp;		

&nbsp;		System.out.println("좋아하는 동물을 입력해주세요.");

&nbsp;		String animal = "강아지";

&nbsp;		String result;

&nbsp;		

&nbsp;		if(animal.equals("강아지")) {

&nbsp;			result = "멍멍!";

&nbsp;		}else if(animal.equals("고양이")){

&nbsp;			result = "야옹!";

&nbsp;		}else {

&nbsp;			result = "무슨 동물이야?";

&nbsp;		}

&nbsp;		

&nbsp;		System.out.println(result);



&nbsp;	}



}





#### 4번

package day1;



import java.util.Scanner;



public class Number4 {



&nbsp;	public static void main(String\[] args) {



&nbsp;		Scanner sc = new Scanner(System.in);

&nbsp;		

&nbsp;		System.out.println("좋아하는 동물을 입력해주세요.");

&nbsp;		String animal = sc.nextLine();

&nbsp;		String result;

&nbsp;		

&nbsp;		if(animal.equals("강아지")) {

&nbsp;			result = "멍멍!";

&nbsp;		}else if(animal.equals("고양이")){

&nbsp;			result = "야옹!";

&nbsp;		}else {

&nbsp;			result = "무슨 동물이야?";

&nbsp;		}

&nbsp;		

&nbsp;		System.out.println(result);





&nbsp;	}



}





#### 5번

package day1;



import java.util.Scanner;



public class Number5 {



&nbsp;	public static void main(String\[] args) {



&nbsp;		Scanner sc = new Scanner(System.in);



&nbsp;		System.out.println("주말일까 평일일까 아무숫자나 넣어보세요");

&nbsp;		int day = sc.nextInt();

&nbsp;		String result = sc.nextLine();

&nbsp;		

&nbsp;		if(day == 0 || day == 6) {

&nbsp;			result = "주말이야!";

&nbsp;		}else {

&nbsp;			result = "평일이야!";

&nbsp;		}

&nbsp;		

&nbsp;		System.out.println(result);

&nbsp;	

&nbsp;		

&nbsp;	}



}





#### 6번

package day1;



import java.util.Scanner;



public class Number5 {



&nbsp;	public static void main(String\[] args) {

&nbsp;		

&nbsp;		Scanner sc = new Scanner(System.in);

&nbsp;		

&nbsp;		System.out.println("주말 맞추기! 아무숫자나 입력해보세요.");

&nbsp;		int number = sc.nextInt();

&nbsp;		String results = sc.nextLine();

&nbsp;		

&nbsp;		switch (number) {

&nbsp;			case 0:

&nbsp;				results = "일요일";

&nbsp;				break;

&nbsp;			case 6:

&nbsp;				results = "토요일";

&nbsp;				break;

&nbsp;			default:

&nbsp;				results = "기타";

&nbsp;				break;

&nbsp;			}

&nbsp;		



&nbsp;		String reresults = results;

&nbsp;		if (results == "일요일" || results == "토요일") {

&nbsp;			reresults = "주말이야!";

&nbsp;		}else if(results == "기타"){

&nbsp;			reresults = "평일이야!";

&nbsp;		}else {

&nbsp;			return;

&nbsp;		}



&nbsp;		System.out.println(number + "는 " + results + "이고, " + reresults);	

&nbsp;	}



}



#### 7번

package day1;



import java.util.Scanner;



public class Number7 {



&nbsp;	public static void main(String\[] args) {



&nbsp;		Scanner sc =  new Scanner(System.in);

&nbsp;		System.out.println("나이를 입력해주세요.");

&nbsp;		int age = sc.nextInt();

&nbsp;		String result;

&nbsp;		// 근데 이건 왜 해야하지?

&nbsp;		

&nbsp;		if (age >= 19) {

&nbsp;			result = "성인입니다.";

&nbsp;		}else {

&nbsp;			result = "미성년입니다.";

&nbsp;		}

&nbsp;				

&nbsp;		System.out.println(result);

&nbsp;		

&nbsp;		sc.close();

&nbsp;	}



}



#### 8번

package day1;



import java.util.Scanner;



public class Number8 {



&nbsp;	public static void main(String\[] args) {



&nbsp;		Scanner sc = new Scanner(System.in);

&nbsp;		

&nbsp;		

&nbsp;		System.out.println("오늘 마신 커피 수를 입력하세요: ");

&nbsp;		int cups = sc.nextInt();

&nbsp;		String result;

&nbsp;		

&nbsp;		

&nbsp;		if(cups == 0) {

&nbsp;			result = "여긴 어디? 😵";

&nbsp;		}else if(cups >= 1 \&\& cups <3) {

&nbsp;			result = "완전 맑은 정신~ 🍀";

&nbsp;		}else {

&nbsp;			result = "기분 좋은 상태! 😄";

&nbsp;		}

&nbsp;		

&nbsp;		System.out.println("당신의 상태는~ " + result);

&nbsp;		

&nbsp;		sc.close();

&nbsp;		

&nbsp;	}



}



#### 9번

package day1;



import java.util.Scanner;



public class Number9 {



&nbsp;	public static void main(String\[] args) {

&nbsp;		

&nbsp;		Scanner sc = new Scanner(System.in);

&nbsp;		

&nbsp;		System.out.println("짝수인지 홀수인지 궁금한 숫자를 넣어보세용");

&nbsp;		int number = sc.nextInt();

&nbsp;		String result = "";

&nbsp;		

&nbsp;		if(number % 2 == 0) {

&nbsp;			result = "짝수";

&nbsp;		}else {

&nbsp;			result = "홀수";

&nbsp;		}

&nbsp;				

&nbsp;		System.out.println("물어보신 숫자인 " + number + "는 " + result + " 입니다.");

&nbsp;		

&nbsp;		sc.close();

&nbsp;		

&nbsp;	}



}







# \#20250909





\##part 01. 자바 언어의 기초

1.1 프로그래밍 언어와 자바

\*고급언어(자바, C, C++, 파이썬 등) -> 컴파일러 -> 하급언어(기계어)



1.2 운영체제별 JDK 설치

\*Java SE(Standard Edition)의 구현체 = JDK(Java Development Kit)

\*JDK 종류 = Open JDK, Oracle JDK

\*LTS(Long Term Support) 버전으로 설치하는 것을 추천 (장기간 기술 지원을 받을 수 있기에 다른 버전보다 안정적임)



1.3 운영체제별 환경 변수 설정

 	1) 환경변수 - 시스템변수 새로만들기 - 변수이름 설정(JAVA\_HOME)

 	2) 환경변수 - 시스템변수 Path 선택 - 새로만들기 - %JAVA\_HOME%\\bin - 첫번째 항목으로 올려주기

 	3) 파워쉘 실행 - "javac -version" - "java -version"

* 운영체제별 환경 변수 설정하는 이유는?
* 운영체제가 프로그램의 경로를 쉽게 찾도록 하거나, 프로그램의 동작 방식을 프로그램 자체를 수정하지 않고 변경할 수 있게 하기 위함.



1.4 바이트코드 파일과 자바 가상 머신

* 자바소스파일(.java) -> javac 명령어 실행(컴파일) -> 바이트코드파일(Hello.class) -> java 명령어 실행 (자바 가상 머신) -> 기계어(010111000...) -> 실행
* 이때 어떤 운영체제라도 컴파일된 바이트코드파일은 동일하지만, 자바 가상 머신은 각각의 운영체제에서 이해하는 기계어로 번역해야하므로 설치하는 JDK가 다른 것임.



1.5 소스 작성부터 실행까지

 	1) 바이트코드  파일이 위치할 패키지 선언

 	2) -

 	3) Hello 클래스 선언

 	4) main() 메소드 선언

 	5) 콘솔에 출력하는 코드

 	6) }

 	7) }

