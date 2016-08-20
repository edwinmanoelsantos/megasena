import java.awt.List;
import java.util.ArrayList;
import java.util.Collections;

public class MegaSena {
   public static void main(String[] args) {
	   ArrayList lista = new ArrayList();
       ArrayList<Integer> possiveis = new ArrayList<Integer>();
       for (int i = 0; i < 60; i++) {
           possiveis.add(i);
       }
       Collections.shuffle(possiveis);

       for (int i = 0; i < 6; i++) {
           System.out.println(possiveis.get(i));
       }
    }
}
