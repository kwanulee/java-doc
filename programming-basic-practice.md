# 자바 프로그래밍 기초 실습

1. 아래 코드에서 잘못된 부분을 적절히 수정하고, 실행결과를 출력하시오

	```java
	public class 실습2_1 {
	    public static void main(String args[]) {
	        boolean a = 10 > 0; 
	        boolean b = 1; 
	        byte c = 128; 
	        short d = 129;
	        int e = 300000;
	        long f = 3.14; 
	        float g = 3.14; 
	        double h = 3.14;
	        char i = 'a';
	        char j = '한';
	        final double PI = 3.142592;
	        
	        System.out.println("c=" + c);
	        PI = 3.14; 
	        System.out.println("PI=" + PI);
	    }
	}
	```

2. 원화를 달러로 환전해 주는 프로그램을 완성하여라. 
	- 원화 액수와 환율은 각각 won, rate 변수에 초기화되어 있다고 가정한다.
	- 환전된  달러를 표시하고, 환전된 달러가 100 달러, 50 달러, 20달러, 10 달러, 5 달러, 2달러, 1달러 지폐 각각 몇 개로 변환되는 지 출력하라. 단 1 달러 이하의 금액은 버린다고 가정한다.

	```java
	public class 실습2_2 { 
	
	    public static void main(String args[]) { 
	        int won = 100000;
	        double rate = 1138;  // 1138 원/달러
	
	        // 여기서부터 코드 추가하세요
	    }
	}
	```	

	- 요구되는 출력 결과
	
	```
	환전한 달러는 총 87 입니다
	100달러 0개, 50달러 1개, 20달러 1개, 10달러 1개, 5달러 1개, 2달러 1개, 1달러 0개 
	```
	