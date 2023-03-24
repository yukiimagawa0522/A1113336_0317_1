# A1113336_0317_1
import java.util.*;

public class A1113336_0317_1{
	public static void main(String[]argv){
		System.out.println("請輸入第一個數字:");

		Scanner n = new Scanner(System.in);
		int N = n.nextInt(); 

		System.out.println("請輸入第二個數字:");

		Scanner m = new Scanner(System.in);
		int M = m.nextInt();

		int x,y;

		for(x=1;x<=N;x++){
			for(y=1;y<=M;y++){
				System.out.print(x*y+",");
			}
			System.out.print("\n");
		}
  }
}
