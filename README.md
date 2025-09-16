# \#tokyo🗼


#20250916

***

package day4;

public class Idol {

	private String name;
	private String position;
	private String groupName;
	private int age;
	
	
	public Idol(String name, String position, String groupName, int age) {
		this.name = name;
		this.position = position;
		this.groupName = groupName;
		this.age = age;
	}


	public String getName() {
		return name;
	}


	public void setName(String name) {
		this.name = name;
	}


	public String getPosition() {
		return position;
	}


	public void setPosition(String position) {
		this.position = position;
	}


	public String getGroupName() {
		return groupName;
	}


	public void setGroupName(String groupName) {
		this.groupName = groupName;
	}


	public int getAge() {
		return age;
	}


	public void setAge(int age) {
		this.age = age;
	}
	
}

***


# \#20250912

#### **배열(Array) 타입**

<배열>

1. 정의 :  많은 양의 값을 다루는 좀 더 효율적인 방법

&nbsp;	       즉, 연속된 공간에 값을 나열시키고, 각 값에 인덱스를 부여해 놓은 자료 구조.

2\. 	특징 - 같은 타입의 값만 관리

&nbsp;	   - 배열의 길이는 늘리거나 줄일 수 없음

3\. 	변수 선언 : 

&nbsp;			***타입\[] 변수;***

			***타입 변수 \[];***

4\. 값 목록으로 배열 생성 : 

&nbsp;			***타입\[] 변수 = { 값0, 값1, 값2, ...};***

&nbsp;			String\[] season = { "Spring", "Summer", "Fall", "Winter"};

&nbsp;			season\[1] = "여름"; //"Summer"를 "여름"으로 항목의 값 변경!

&nbsp;								     이렇게 선언하고 나면, 앞으로 seaon\[1]은 Summer가 아니라 여름으로 나옴

&nbsp;	      \*\*배열 변수를 미리 선언한 후에는 값 목록을 변수에 대입할 수 없다\*\*

5\. new 연산자로 배열 생성 :

&nbsp;	      값의 목록은 없지만 향후 값들을 저장할 목적으로 배열 미리 생성 가능

&nbsp;	      ***타입\[] 변수 = new 타입\[길이];***

&nbsp;	      new 연산자로 배열을 처음 생성하면 배열 항목은 기본값으로 초기화 (초기값 거의 0)

6\. 배열 길이 : 배열에 저장할 수 있는 항몫.

&nbsp;			      ***배열변수.length;***

&nbsp;			      이때, for 문 조건식에서 < 연산자를 사용한 이유는 배열 시작이 0이기 때문







<인덱스>

1. 정의 : \[] 대괄호와 함께 사용











# \#20250911

#### 1번

package day1;



import java.util.Scanner;



public class Number2 {



 	public static void main(String\[] args) {

 



 		System.out.println("비밀번호를 입력하세요.");

 		String password = "qwer1234";

 		String result;

 

 		if(password.equals("qwer1234")) {

 			result = "비밀번호가 맞아요!";

 		}else {

 			result = "비밀번호가 틀렸어요!";

 		}

 

 		System.out.println(result);

 

 

 	}



}

#### 2번

 package day1;



import java.util.Scanner;



public class Number1 {



 	public static void main(String\[] args) {

 

 		Scanner sc = new Scanner(System.in);

 

 		System.out.println("비밀번호를 입력하세요.");

 		String password = sc.nextLine();

 		String result;

 

 		if(password.equals("qwer1234")) {

 			result = "비밀번호가 맞아요!";

 		}else {

 			result = "비밀번호가 틀렸어요!";

 		}

 

 		System.out.println(result);

 

 		sc.close();



 	}



}



#### 3번

package day1;



public class Number3 {



 	public static void main(String\[] args) {

 

 		System.out.println("좋아하는 동물을 입력해주세요.");

 		String animal = "강아지";

 		String result;

 

 		if(animal.equals("강아지")) {

 			result = "멍멍!";

 		}else if(animal.equals("고양이")){

 			result = "야옹!";

 		}else {

 			result = "무슨 동물이야?";

 		}

 

 		System.out.println(result);



 	}



}





#### 4번

package day1;



import java.util.Scanner;



public class Number4 {



 	public static void main(String\[] args) {



 		Scanner sc = new Scanner(System.in);

 

 		System.out.println("좋아하는 동물을 입력해주세요.");

 		String animal = sc.nextLine();

 		String result;

 

 		if(animal.equals("강아지")) {

 			result = "멍멍!";

 		}else if(animal.equals("고양이")){

 			result = "야옹!";

 		}else {

 			result = "무슨 동물이야?";

 		}

 

 		System.out.println(result);





 	}



}





#### 5번

package day1;



import java.util.Scanner;



public class Number5 {



 	public static void main(String\[] args) {



 		Scanner sc = new Scanner(System.in);



 		System.out.println("주말일까 평일일까 아무숫자나 넣어보세요");

 		int day = sc.nextInt();

 		String result = sc.nextLine();

 

 		if(day == 0 || day == 6) {

 			result = "주말이야!";

 		}else {

 			result = "평일이야!";

 		}

 

 		System.out.println(result);

 

 

 	}



}





#### 6번

package day1;



import java.util.Scanner;



public class Number5 {



 	public static void main(String\[] args) {

 

 		Scanner sc = new Scanner(System.in);

 

 		System.out.println("주말 맞추기! 아무숫자나 입력해보세요.");

 		int number = sc.nextInt();

 		String results = sc.nextLine();

 

 		switch (number) {

 			case 0:

 				results = "일요일";

 				break;

 			case 6:

 				results = "토요일";

 				break;

 			default:

 				results = "기타";

 				break;

 			}

 



 		String reresults = results;

 		if (results == "일요일" || results == "토요일") {

 			reresults = "주말이야!";

 		}else if(results == "기타"){

 			reresults = "평일이야!";

 		}else {

 			return;

 		}



 		System.out.println(number + "는 " + results + "이고, " + reresults);

 	}



}



#### 7번

package day1;



import java.util.Scanner;



public class Number7 {



 	public static void main(String\[] args) {



 		Scanner sc =  new Scanner(System.in);

 		System.out.println("나이를 입력해주세요.");

 		int age = sc.nextInt();

 		String result;

 		// 근데 이건 왜 해야하지?

 

 		if (age >= 19) {

 			result = "성인입니다.";

 		}else {

 			result = "미성년입니다.";

 		}

 

 		System.out.println(result);

 

 		sc.close();

 	}



}



#### 8번

package day1;



import java.util.Scanner;



public class Number8 {



 	public static void main(String\[] args) {



 		Scanner sc = new Scanner(System.in);

 

 

 		System.out.println("오늘 마신 커피 수를 입력하세요: ");

 		int cups = sc.nextInt();

 		String result;

 

 

 		if(cups == 0) {

 			result = "여긴 어디? 😵";

 		}else if(cups >= 1 \&\& cups <3) {

 			result = "완전 맑은 정신~ 🍀";

 		}else {

 			result = "기분 좋은 상태! 😄";

 		}

 

 		System.out.println("당신의 상태는~ " + result);

 

 		sc.close();

 

 	}



}



#### 9번

package day1;



import java.util.Scanner;



public class Number9 {



 	public static void main(String\[] args) {

 

 		Scanner sc = new Scanner(System.in);

 

 		System.out.println("짝수인지 홀수인지 궁금한 숫자를 넣어보세용");

 		int number = sc.nextInt();

 		String result = "";

 

 		if(number % 2 == 0) {

 			result = "짝수";

 		}else {

 			result = "홀수";

 		}

 

 		System.out.println("물어보신 숫자인 " + number + "는 " + result + " 입니다.");

 

 		sc.close();

 

 	}



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

