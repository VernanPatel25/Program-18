import java.util.*;
class Series
{
    double a,n,sum=0;
    void init()
    {
        Scanner sc=new Scanner(System.in);
        a=sc.nextDouble();
        n=sc.nextDouble();
        double ans1=function(n);
        double ans2=function(n,a);
        disp(ans1,ans2);
    }
    double function(double n1)
    {
        for(int i=(int)n1;i>1;i++)
        {
            sum+=(1/i);
        }
        System.out.println();
        return(sum);
    }
