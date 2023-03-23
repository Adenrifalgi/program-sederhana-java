import java.util.Scanner;

public class HitungGajiLembur {
    public static void main(String[] args) {
        Pemindai pemindai = Pemindai baru (System.in);

        System.out.print("Masukkan gaji pokok: Rp");
        double gajiPokok = scanner.nextDouble();

        System.out.print("Masukkan selai lembur: ");
        double jamLembur = scanner.nextDouble();

        System.out.print("Masukkan upah lembur per jam: Rp");
        double upahLembur = scanner.nextDouble();

        gajiBersih ganda = gajiPokok + (jamLembur * upahLembur);

        System.out.println("Gaji bersih: Rp" + gajiBersih);
    }
}
