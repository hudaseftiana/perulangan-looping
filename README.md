# perulangan-looping
looping atau perulangan adalah sebuah perintah untuk menunjukkan perulangan sebuah nilai baik angka maupun tulisan sebanyak yang diinginkan yang di inputkan melalui program. perintah yang digunakan ialah for, while, do-while.

//IO menggunakan Scanner
public class IO {
    public static void main(String[] args) {
        //membahas IO
        Scanner inputNilai = new Scanner (System.in);
        System.out.println("Inputkan Nilai Angka 0-100");
        int nilai = inputNilai.nextInt();
        System.out.println("Nilai : " + nilai);
        if(nilai >= 91 && nilai <= 100){
            System.out.println("A");
       }else if(nilai >=86 && nilai <=90){
           System.out.println("A-");
       }else if (nilai >= 81 && nilai <= 85){
           System.out.println("B+");
       }else if (nilai >=76 && nilai <=80){
           System.out.println("B");
       }else if (nilai >= 71 && nilai <=75){
           System.out.println("B-");
       }else if (nilai >=66 && nilai <= 70){
           System.out.println("C+");
       }else if (nilai >= 61 && nilai <=65){
           System.out.println("C");
       }else if (nilai >= 56 && nilai <=60){
           System.out.println("C-");
       }else if (nilai >= 51 && nilai <= 55){
           System.out.println("D");
       }else{
           System.out.println("E");
       }
        
    }
    
}

//IO menggunakan JOptionPane
public class IO2 {
    public static void main(String[] args) {
        //IO versi JOption
        String inputnilai = JOptionPane.showInputDialog("inputnilai");
        int nilai = Integer.parseInt(inputnilai);
        if(nilai >= 91 && nilai <= 100){
            System.out.println("A");
       }else if(nilai >=86 && nilai <=90){
           System.out.println("A-");
       }else if (nilai >= 81 && nilai <= 85){
           System.out.println("B+");
       }else if (nilai >=76 && nilai <=80){
           System.out.println("B");
       }else if (nilai >= 71 && nilai <=75){
           System.out.println("B-");
       }else if (nilai >=66 && nilai <= 70){
           System.out.println("C+");
       }else if (nilai >= 61 && nilai <=65){
           System.out.println("C");
       }else if (nilai >= 56 && nilai <=60){
           System.out.println("C-");
       }else if (nilai >= 51 && nilai <= 55){
           System.out.println("D");
       }else{
           System.out.println("E");
       }
    }
}
