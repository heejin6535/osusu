```java
package day11.quiz;

public class FunctionFactory {
	/* strGugudan()
	 *  인자값 : 정수 1개 
	 *  하는 일 : 해당 구구단 1개의 문자열로 만들기 
	 *  리턴값 : 구구단 문자열 ("2 X 1 = 2 \n2 X 2 = 4 \n2 X 3 = 6\n...")
	 */
	String strGugudan (int gugudan) {
		String a;
		a = gugudan + "단\n";
		for(int b = 1; b <=9; ++b) {
			a += gugudan + "X" + b + "=" +gugudan*b + "\n";
		}
		return a;
	}
	
	/* printGugudan()
	 *  인자값 : 정수 1개 
	 *  하는 일 : 해당 구구단을 sysout
	 *  리턴값 : 없음
	 */
	
	void printGugudan(int ggd) {
		String g;
		g = ggd + "단\n";
		for(int a = 1; a <= 9; ++a) {
			System.out.println(ggd + "X" + a + "=" + ggd*a);
		}
	}
	
	/* getAverage()
	 *  인자값 : 국, 영, 수
	 *  하는 일 : 국, 영, 수 평균 계산
	 *  리턴값 : 평균값
	 */
	
	double getAverage(int kr, int en, int ma) {
		double avg;
		avg = (kr+en+ma) / 3.0;
		return avg;
	}
	
	 /* getRandomPokemon()
		 *  인자값 : X
		 *  하는 일 : "피카츄", "라이츄", "파이리", "꼬부기" 중 1개의 포켓몬을 랜덤으로 뽑기
		 *  		(Math.random() 사용)
		 *  리턴값 : 뽑힌 포켓몬 이름 
		 */
	
	String getRandomPokemon() {
		String a, b, c, d;
		a = "피카츄";
		b = "라이츄";
		c = "파이리";
		d = "꼬부기";
		
		
	}
	
	 /* getMax()
		 *  인자값 : int형 배열 1개 
		 *  하는 일 : 이 배열의 원소 중 가장 큰 수 찾기
		 *  리턴값 : 가장 큰 수
		 */
	
	int getMax(int[] arr) {
		int max = Integer.MAX_VALUE;
		return arr[max];
	}
	
	}
```
