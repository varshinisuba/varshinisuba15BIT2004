import java.util.*;
public class Main
{
	public static void main(String[] args) 
	{
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int c=sc.nextInt();
	    int a[]=new int[n];
	    int sum=0;
	    for(int i=0;i<n;i++)
	    {
	        a[i]=sc.nextInt();
	    }
	    Arrays.sort(a);
	    for(int j=0;j<c;j++)
	    {
	        sum=sum+a[j];
	    }
	    System.out.println(sum);
	    
	}
}


