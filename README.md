# Cube-SquareRootJava

public class CubeSquareRootExample {

    public static void main(String[] args) {
        double cube = 125.0d;
        double square = 100.0d;

        // 
        // Get the cube root of double value
        //
        double cbrt = Math.cbrt(cube);
        System.out.println("Cube root of " + cube + " is " + cbrt);

        //
        // Get the square root of double value
        //
        double sqrt = Math.sqrt(square);
        System.out.println("Square root of " + square + " is " + sqrt);
    }

}
 
Output
Cube root of 125.0 is 5.0
Square root of 100.0 is 10.0
