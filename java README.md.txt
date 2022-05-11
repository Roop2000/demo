import java.util.*;
public class mulTable {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		
		System.out.println("enter a number");
		
		for(int i=1; i<=n; i++) {
			if (n%2==0) {
			System.out.println(i+" X " +n+ "= " +i*n );
			}
		}
		// TODO Auto-generated method stub
		

	}

}
