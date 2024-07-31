# LINEAR-SEARCH
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
      int []a={1,2,3,4,5,6,7,8,87,90};
      Scanner sc=new Scanner(System.in);
      int k=sc.nextInt();
      int p=0;
      for(int i=0;i<10;i++){
          if (a[i]==k){
              p=1;
               System.out.println("Number was found at index "+i);
               break;
          }
      }
      if (p==0){
           System.out.println("number not found");
      }
    }
}
