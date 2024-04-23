import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        String a=new String();
        a=s.nextLine();
        String b="";
        int x=a.length();
        for(int i=x-1;i>=0;i--){
            b+=a.charAt(i);
        }
        System.out.print(b);
    }
}