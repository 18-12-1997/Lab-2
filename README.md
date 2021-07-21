# Lab-2
1. public class Main{
    public static void main (String[]args)
    {
        //declaration of variables
        int a=20, b=10;
        int sum, sub,mul,div;
        sum=a+b;
        sub=a-b;
        mul=a*b;
        div=a/b;
       
        System.out.println("value of a is: " + a);
        System.out.println("value of b is: " + b);
        System.out.println("the sum of "+a+" and "+b+" is: " + sum);
        System.out.println("the difference of "+a+" and "+b+" is: " + sub);
        System.out.println("the product of "+a+" and "+b+" is: " + mul);
        System.out.println("the division of "+a+" and "+b+" is: " + div);
        
         }
}
2. public class Main
{
	public static void main(String[] args) {
	    
	    String dna="ATACGATACAA";
		System.out.println("The dna is:" +dna);
	}
}
3. public class Main{
    public static void main(String[] args){
        String dna1="AATCGTCGATCGCTCT";
        String dna2="TGCACGTAAAAC";
        String DNA;
        DNA=dna1+dna2;
        System.out.println("The new DNA is: " + DNA);
         }
}
4. public class Main{
    public static void main(String[] args){
       int n1= 0;
       int n2= 1;
       int i, n3;
        for(i=0; i<=25; i++) 
        {    
              n3=n1+n2;
             System.out.println(n3);
              n1=n2;
              n2=n3;
      }
   }
}
5. public class Main
{
	public static void main(String[] args) {
	float avg;
	int i;
	float sum=0;
	double[] arr={1,2,3,4,5,6,7,8,9,10};
	for(i=0;i<10;i++)
	{
	    sum+=arr[i];
	}
	avg=sum/10;
	System.out.println(avg);
	
	}
}
6. 
