# Java-using-Palindrome-use-temp
import java.util.Scanner;
public class Main
{
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int temp = n;
        int rev=0;
        for(; n>0; rev*=10+n%10, n/=10);
        System.out.println((temp==rev)?"Yes":"No");
        
    }
}
