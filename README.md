# Reversing-Digit
Java Code for Reversing the Digits of a Number

public class ReverseDigit {
    private int rev=0;
    public int reverse(int num){
        while(num!=0){
            rev = rev*10 + num%10;
            num = num/10;
        }
        return rev;
    }
}
