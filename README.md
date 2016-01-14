# ForLoopMeasure

public class Exercise04_06 {
    public Exercise04_06() {
    }

    public static void main(String[] args) {
        System.out.printf("%10s%10s    |  %10s%10s\n", new Object[]{"Miles", "Kilometers", "Kilometers", "Miles"});
        System.out.println("---------------------------------------------");
        int miles = 1;
        int kilometers = 20;

        for(int count = 1; count <= 10; ++count) {
            System.out.printf("%10d%10.3f    |  %10d%10.3f\n", new Object[]{Integer.valueOf(miles), Double.valueOf((double)miles * 1.609D), Integer.valueOf(kilometers), Double.valueOf((double)kilometers / 1.609D)});
            ++miles;
            kilometers += 5;
        }

    }
}
