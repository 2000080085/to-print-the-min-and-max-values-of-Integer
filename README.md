# to-print-the-min-and-max-values-of-Integer
public class Arrays {
	public static void main(String[] args) {
		int []arr=new int[10];
		int leng=arr.length;
		for(int i=0;i<len;i++)
		{
			arr[i]=Integer.parseInt(args[i]);
		}
		int sum=0;
		for(int i=0;i<leng;i++)
			sum=sum+arr[i];
		System.out.println("Sum is"+sum);
		System.out.println("Average is"+(sum/(float)leng));
		int max=Integer.MAX_VALUE;
		int min=Integer.MIN_VALUE;
		System.out.println("Mamximum value "+Integer.MAX_VALUE);
		System.out.println("Minimum value"+Integer.MIN_VALUE);
		


}
}
