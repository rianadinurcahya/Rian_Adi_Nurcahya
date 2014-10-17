Rian_Adi_Nurcahya
=================

SI13F_RianAdiNurcahya_13311112T_TugasInput
package tugasinput;

import java.util.Scanner;

public class NewMainRian {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        //deklarasi
        String nama, npm, kelas, tgl, alamat;
        //inputan
        System.out.print("masukkan nama anda mas BRO..         :");
        nama = input.nextLine();
        
        System.out.print("masukkan NPM anda mas BRO..          :");
        npm = input.nextLine();
        
        System.out.print("anda masuk kelas apa mas BRO..       :");
        kelas = input.nextLine();
        
        System.out.print("masukkan tanggal lahir anda mas BRO..:");
        tgl = input.nextLine();
        
        System.out.print("alamat anda dimana mas BRO..         :");
        alamat = input.nextLine();

        
       //output
        System.out.println("Nama Anda Adalah..   :"+nama);
        System.out.println("NPM anda..           :"+npm);
        System.out.println("Anda Berada Dikelas..:"+kelas);
        System.out.println("tanggal lahir anda.. :"+tgl);
        System.out.println("Alamat Anda..        :"+alamat);


        
        
    }
    
}
