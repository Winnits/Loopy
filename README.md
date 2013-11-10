package winnits;
/**
 *
 * @author Winnits
 */
public class Practice {
 
    public static void add(int a, int b){
        int answer = a * b;
     if (a <= 100 && a >= 0){
         if (b <=100 && b >=0){
             System.out.println(answer);
         }else
             System.out.println("Number b must be below 100 and above 0");
     }  else
         System.out.println("Number a must be below 100 and above 0");
    }
  public static void main (String args[]){
      int count1 = 0;
      int count2 = 100;
   while(count1 <= 100 && count2 >=0){
          add(count1, count2);
          
          count1++;
          count2--;
      }
      
       }
}

