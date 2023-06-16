# introdution-of-java
AVERAGE MARKS 
import java.util.Scanner;
public class Solution {


	public static void main(String[] args) {
		
        Scanner s = new Scanner(System.in);
        String name;
        int m1,m2,m3;
        name =s.next();
        m1= s.nextInt();
        m2= s.nextInt();
        m3= s.nextInt();
        int avg = (m1+m2+m3)/3;
        System.out.println(name);
        System.out.println(avg);

		
	}

}
