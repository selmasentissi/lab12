# lab12
import java.io.BufferedReader;
import java.io.FileReader;
import java.nio.Buffer;

public class test <BinaryTree> {
	
	BinaryTree tree = new BinaryTree();
	
	
	public static void read ()
	{
	
		try 
		{
			FileReader c = new FileReader ("students.in");
			BufferedReader r = new BufferedReader(c);
			
			String line = r.readLine();
			
			System.out.println(line);
			 while (line!= null)
			 {
				 line.split(line);
				 line = r.readLine();
			 }
		}
		catch (Exception e)
		{
			throw new Error (e);
		}
		 
		
	}
	

	public static void main(String[] args) {
		read();

	}
	
	public void test123 ()
	{
		for ( int i = 0 ; i <= line ; i++)
		{
			line(i).compareTo(line(i++));
			
		}
	}

}
