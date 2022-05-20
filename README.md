# Coding-save
My modification about all kinds of coding
import java.util.List;
import java.util.Arrays;

public class HelloWorld{

     public static void main(String []args){
        System.out.println("Hello World");
       // List<Integer> l = new ArrayList<>();
        
        List<Integer> result = new ArrayList<Integer>();
        int[] array = new int[]{1, 2};
        List<Integer> tem = Arrays.asList(array);
        result.add(tem);
       // System.out.print(result);
     }
}
