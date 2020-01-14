import java.sql.SQLOutput;
import java.util.*;

public class men {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int ar[]=new int[10];
        int i,s=0;
        for(i=0;i<10;i++)
        {
            ar[i]=sc.nextInt();

        }
        for(i=0;i<10;i++)
        {
           s=s+ ar[i];

        }
        System.out.println(s/10);
    }
}
