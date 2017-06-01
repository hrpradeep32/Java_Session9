import java.util.ArrayList;
import java.util.HashSet;
import java.util.Iterator;


public class CollectionDuplicates {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		ArrayList<Integer> ar=new ArrayList<Integer>();
		ar.add(20);
		ar.add(30);
		ar.add(40);
		ar.add(10);
		ar.add(20);
		ar.add(70);
		ar.add(40);
		ar.add(30);
		ar.add(90);
		ar.add(10);
		HashSet<Integer> hs=new HashSet<Integer>();
		for(int i=0;i<ar.size();i++)
		{
			hs.add(ar.get(i));
		}
		System.out.println("collection data after removing duplicates is ");
		Iterator<Integer> it=hs.iterator();
		while(it.hasNext())
		{
			System.out.println(it.next());
		}
	}
}
