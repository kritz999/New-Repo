# New-Repo
import java.util.*;
public class Strings {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("enter the value of a string");
        String str = sc.nextLine();
        int count1=0; int count2=0;
        for(int i=0;i<str.length();i++){
          if(str.charAt(i)=='*'){
              count1++;
          } if(str.charAt(i)=='#'){
              count2++;
          }
        }
        if(count1==count2){
            System.out.println(0);
        }
        else{
            System.out.println(count1-count2);
        }

    }
}

