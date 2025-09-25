import java.util.Scanner;

public class MediaEscolar {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double[] notas = new double[8];

        // Lê as 8 notas
        for (int i = 0; i < 8; i++) {
            System.out.print("Digite a nota do " + (i + 1) + "º bimestre: ");
            notas[i] = sc.nextDouble();
        }

        // Médias bimestrais já são as próprias notas
        // Médias semestrais
        double semestre1 =
