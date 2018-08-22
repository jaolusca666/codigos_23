# codigos_23
import java.util.Scanner;
public class bascara {
    public static void main(String[] args) {
        Scanner tcl = new Scanner(System.in);
        int a = tcl.nextInt();
        int b = tcl.nextInt();
        int c = tcl.nextInt();
        int delta = b^2 - 4 * a * c;
        double x1 = (-1 *b +(delta)^1/2)/2*a;
        double x2 = (-1 *b -(delta)^1/2)/2*a;
        System.out.println("x1 vale:"+x1 );
        System.out.println("x2 vale:"+x2 );
        if(a > 0){
            System.out.println("a parabola é para cima");
        }else{
            System.out.println("a parabola é para baixo");
        }
        
    
    }
}
