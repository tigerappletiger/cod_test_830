# cod_test_831
코드 테스트 하루 한문제 풀기
//2차원 배열에 값을 넣어 출력하시오
package cod_test;

import java.util.Scanner;

public class Test_831 {

	public static void main(String[] args) {
		Scanner sc= new Scanner(System.in);
		System.out.println("1행 1열과 1행 2열에 각각 저장될 정수를 입력하시오: ");
		int [][]arr=new int[2][2];
		for (int i = 0; i < arr.length; i++) {
			for (int j = 0; j <arr.length; j++) {
				int input= sc.nextInt();
				arr[i][j]=input;
				System.out.println("arr["+i+"]["+j+"] :");
			}
		}
		for (int i = 0; i < arr.length; i++) {
			for (int j = 0; j < arr.length; j++) {
				System.out.print("arr["+i+"]["+j+"] :"+arr[i][j]+" , ");
			}
			System.out.println();
		}
	}

}
