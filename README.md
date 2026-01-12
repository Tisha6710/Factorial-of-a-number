# Factorial-of-a-number
package Recursion;

public class factorial {

    static int fact(int n){
        if(n==0) return 1;

        int num=fact( n-1);

        int ans = n*num;
        return ans;
    }

    public static void main(String[] args) {
        System.out.println(fact (4));
    }

}
