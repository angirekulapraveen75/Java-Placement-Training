import java.util.Scanner;
class sumofnatirualnumber
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n, sum;
        System.out.println("enter the value of n:");
        n=sc.nextInt();
        while(n>0)
        {
            sum=(n*(n+1))/2;
        }
        System.out.println("the result is:" + sum);
    }
}
