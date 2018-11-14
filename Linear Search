package tugas4;

import java.util.ArrayList;
import java.util.Scanner;

public class linearsearch {

	public static void main(String[] args) {
		// PREPARING data
		ArrayList<Double> data = new ArrayList<Double>();
		data.add(3.1);
		data.add(12.1);
		data.add(15.4);
		data.add(5.8);
		data.add(21.3);
		data.add(2.0);
		data.add(9.6);
		

		//  DATA INPUT
		System.out.println("Data : " + data.toString());		
		
		Scanner s = new Scanner(System.in);
		System.out.print("Masukkan kunci pencarian: ");
		double key	= s.nextDouble();
		
		int posisi = -1;//jika setelah proses pencarian posisi tetap = -1 berarti key tidak ditemukan pada data
		
		//BEGIN PENCARIAN LINEAR
		for(int i=0;i<data.size();i++){
			if(key==data.get(i)){
				posisi = i;
				break;
			}
		}
		//END OF PENCARIAN LINEAR
		
		//TAMPILKAN HASIL PENCARIAN
		if(posisi!=-1){//Jika nilai posisi tidak sama dengan -1 berarti data ditemukan
			System.out.println("KEY: "+key+" Berada di index array list: "+posisi);
		}else{
			System.out.println("KEY TIDAK DITEMUKAN");
		}	
	}

}

