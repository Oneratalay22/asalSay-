public class Main {
    public static void main(String[] args) {

      
        for (int n = 2; n < 100; n++) {
            boolean Asal = true;
            for (int k = 2; k <= Math.sqrt(n); k++) { 
                if (n % k == 0) {
                    Asal = false;
                    break;
                }
            }   if (Asal) {
                System.out.println(n + " asal sayıdır.");

            }
        }
    }
}
