# PF---Assignment
Qno. 4


// Online Java Compiler
// Use this editor to write, compile and run your Java code online

   public class OriginalPrice {
    public static void main(String[] args) {

        double discountedPrice = 1400;
        double discountPercent = 20;

        double originalPrice = discountedPrice / (1 - (discountPercent / 100));

        System.out.println("Original Selling Price = " + originalPrice);
    }
}
