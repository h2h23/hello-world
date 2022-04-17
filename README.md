# hello-world
my shujuk
package yi;

public class h {
public static void main(String[] args) {
	loop1:
		for(int i=0;i<4;i++) {
			loop2:
				for(int j=0;j<i;j++) {
					if(j==1)continue loop2;
					if(j==3)break loop1;
					System.out.println("loop");
				}
		}
}

}
