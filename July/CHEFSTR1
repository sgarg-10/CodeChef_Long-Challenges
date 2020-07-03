import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    try{
	Scanner s=new Scanner(System.in);
	int t=s.nextInt();
	while(t-- >0){
	    long c=0;
	    int n=s.nextInt();
	    long[] a=new long[n];
	    for(int i=0;i<n;i++){
	        a[i]=s.nextLong();
	    }
	    
	    for(int i=0;i<n-1;i++){
	        if(a[i+1]>a[i]){
	            c=c+(a[i+1]-a[i]-1);
	        }else if(a[i+1]<a[i]){
	            c=c+(a[i]-a[i+1]-1);
	        }
	    }
	    System.out.println(c);
	    
	}}catch(Exception e){
	    return;
	}
	}
}
