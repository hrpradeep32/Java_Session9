import java.util.HashMap;
import java.util.Iterator;
import java.util.Map;
import java.util.Set;


public class EmployeeMap {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		HashMap<Integer,String> hm=new HashMap<Integer,String>();
		hm.put(1234,"ABC");
		hm.put(1235,"BCD");
		hm.put(1236,"CDE");
		hm.put(1237,"DEF");
		hm.put(1238,"EFG");
		hm.put(1239,"FGH");
		hm.put(1240,"GHI");
		Set s=hm.entrySet();
		Iterator it=s.iterator();
		while(it.hasNext())
		{
			Map.Entry mpe=(Map.Entry)it.next();
			System.out.println(mpe.getValue());
		}
	}

}
