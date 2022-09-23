# ***🌟Give Star If you find this helpful :)🌟***
# 1. ***Mirror Image Number Pattern***
### Code:Mirror Image Number Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		 Scanner scan=new Scanner(System.in);
        int num=scan.nextInt();
        int i=1;
        while(i<=num){
            int j=1;
            while(j<=num-i){
                System.out.print(" ");
                j++;
            }
            j=1;
            while(j<=i){
                System.out.print(j);
                j++;
            }
            System.out.println();
            i++;
        }
	}

}

# 2. ***Inverted Number Pattern***
### Code:Inverted Number Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		Scanner scan=new Scanner(System.in);
        int num=scan.nextInt();
        int i=1;
        while(i<=num){
            int j=0+i;
            while(j<=num){
                System.out.print(num-i+1);
                j++;
            }
            System.out.println();
            i++;
        }	
	}

}

# 3. ***Star Pattern***
### Code:Star Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {	
	 Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i = 1;
        while (i <= n) {
            int s = 1;
            while (s <= n - i) {
                System.out.print(" ");
                s++;
            }
            int j = 1, p = 1;
            while (j <= i) {
                System.out.print("*");
                p++;
                j++;
            }
            j = 1;
            p = i - 1;
            while (j <= i - 1) {
                System.out.print("*");
                p--;
                j++;
            }
            System.out.println();
            i++;
        }	
	}

}

# 4. ***Triangle of Numbers***
### Code:Triangle of Numbers

import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		 Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i = 1;
        while (i <= n) {
            int s = 1;
            while (s <= n - i) {
                System.out.print(" ");
                s++;
            }
            int j = 1, p = 0;
            while (j <= i) {
                System.out.print(p+i);
                p++;
                j++;
            }
            j = 1;
            p = p+i-j-1;
            while (j <= i - 1) {
                System.out.print(p);
                p--;
                j++;
            }
            System.out.println();
            i++;
        }
	}

}

# 5. ***Diamond of stars***
### Code:Diamond of stars
import java.util.Scanner;
public class Solution {
    
    public static void main(String[] args) {
         Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i = 1;
        int j;
        int n1=(n+1)/2;
        while (i <= n1) {
            j = 1;
            while (j++ <= n1 - i)
            {
                System.out.print(" ");
            }
            j = 1;
            while (j++ <= i * 2 - 1)
            {
                System.out.print("*");
            }
            System.out.println();
            i++;
        }
        i = n1 - 1;
        while (i > 0) {
            j = 1;
            while (j++ <= n1 - i)
            {
                System.out.print(" ");
            }
            j = 1;
            while (j++ <= i * 2 - 1)
            {
                System.out.print("*");
            }
            System.out.println();
            i--;
        }
    }

}

# ***🌟Give Star If you find this helpful :)🌟***
