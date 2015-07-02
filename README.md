# array
display array elements using for loop and for each


public class Array
{
	public static void main(String agrs[])
	{
		String student[]={"raj","ravi","ramya","saranya","srini","vijay","hsejar","nagarajan","guru","vicky"};
		int n=student.length;
		
		//using for loop
		/*for(int i=0;i<n;i++)
		{
			System.out.println("the value of "+i+"   is  :"+student[i]);
		}*/
		
		
		//using for each
		for(String element:student)
		{
			System.out.println(element);
		}
		
		
		
	}

}
