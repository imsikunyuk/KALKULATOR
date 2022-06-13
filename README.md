<p>KALKULATOR C++<br><br>Program kalkulator sederhana dengan menggunakan bahasa pemrograman C++<br><br>SOURCE CODE<br><br>// PROGRAM = KALKULATOR SEDERHANA C++ 
// PEMBUAT = ROFI

#include <iostream>// PEMBUAT = ROFI
#include <conio.h>// PEMBUAT = ROFI

using namespace std;// PEMBUAT = ROFI

int main(){// PEMBUAT = ROFI
	
	float bilangan_pertama,bilangan_kedua,hasil;// PEMBUAT = ROFI
	string jenis_operator;// PEMBUAT = ROFI
	string coba;// PEMBUAT = ROFI
	
	jenis_operator:// PEMBUAT = ROFI
		cout << "+==========================+\n";// PEMBUAT = ROFI
		cout << "| Kalkulator sederhana C++ |\n";// PEMBUAT = ROFI
		cout << "+==========================+\n";// PEMBUAT = ROFI
		cout << "[!] Jenis operator\n";// PEMBUAT = ROFI
		cout << "[+] Penjumlahan\n";// PEMBUAT = ROFI
		cout << "[-] Pengurangan\n";// PEMBUAT = ROFI
		cout << "[x] Perkalian\n";// PEMBUAT = ROFI
		cout << "[:] Pembagian\n";// PEMBUAT = ROFI
		cout << "+==========================+\n";// PEMBUAT = ROFI
		cout << "[*] Bilangan pertama: ";// PEMBUAT = ROFI
		cin >> bilangan_pertama;// PEMBUAT = ROFI
		cout << "[*] Jenis operator: ";// PEMBUAT = ROFI
		cin >> jenis_operator;// PEMBUAT = ROFI
		cout << "[*] Bilangan kedua: ";// PEMBUAT = ROFI
		cin >> bilangan_kedua;// PEMBUAT = ROFI
		
		if (jenis_operator == "+"){// PEMBUAT = ROFI
			hasil = bilangan_pertama + bilangan_kedua;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Hasil = " << hasil << endl;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Mau coba lagi (iya/tidak): ";// PEMBUAT = ROFI
			cin >> coba;// PEMBUAT = ROFI
			if (coba == "iya"){// PEMBUAT = ROFI
				cout << "+==========================+\n\n";// PEMBUAT = ROFI
				goto jenis_operator;// PEMBUAT = ROFI
			}// PEMBUAT = ROFI                                                  	
			else if (coba == "tidak"){// PEMBUAT = ROFI                            
				cout << "+==========================+\n";// PEMBUAT = ROFI          GA BISA NGODING JANGAN NGAKUIN SOURCE ORANG!
				cout << "[!] Terimakasih.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else {// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Program error.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
		}// PEMBUAT = ROFI
		else if (jenis_operator == "-"){// PEMBUAT = ROFI
			hasil = bilangan_pertama - bilangan_kedua;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Hasil = " << hasil << endl;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Mau coba lagi (iya/tidak): ";// PEMBUAT = ROFI
			cin >> coba;// PEMBUAT = ROFI
			if (coba == "iya"){// PEMBUAT = ROFI
				cout << "+==========================+\n\n";// PEMBUAT = ROFI
				goto jenis_operator;// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else if (coba == "tidak"){// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Terimakasih.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else {// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Program error.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
		}// PEMBUAT = ROFI
		else if (jenis_operator == "x"){// PEMBUAT = ROFI
			hasil = bilangan_pertama * bilangan_kedua;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Hasil = " << hasil << endl;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Mau coba lagi (iya/tidak): ";// PEMBUAT = ROFI
			cin >> coba;// PEMBUAT = ROFI
			if (coba == "iya"){// PEMBUAT = ROFI
				cout << "+==========================+\n\n";// PEMBUAT = ROFI
				goto jenis_operator;// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else if (coba == "tidak"){// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Terimakasih.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else {// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Program error.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
		}// PEMBUAT = ROFI
		else if (jenis_operator == ":"){// PEMBUAT = ROFI
			hasil = bilangan_pertama / bilangan_kedua;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Hasil = " << hasil << endl;// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Mau coba lagi (iya/tidak): ";// PEMBUAT = ROFI
			cin >> coba;// PEMBUAT = ROFI
			if (coba == "iya"){// PEMBUAT = ROFI
				cout << "+==========================+\n\n";// PEMBUAT = ROFI
				goto jenis_operator;// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else if (coba == "tidak"){// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Terimakasih.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else {// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Program error.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
		}// PEMBUAT = ROFI
		else {// PEMBUAT = ROFI
			cout << "+==========================+\n";// PEMBUAT = ROFI
			cout << "[!] Operator tidak tersedia, mau coba lagi (iya/tidak): ";// PEMBUAT = ROFI
			cin >> coba;// PEMBUAT = ROFI
			if (coba == "iya"){// PEMBUAT = ROFI
				cout << "+==========================+\n\n";// PEMBUAT = ROFI
				goto jenis_operator;// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else if (coba == "tidak"){// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Terimakasih.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			else {// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
				cout << "[!] Program error.\n";// PEMBUAT = ROFI
				cout << "+==========================+\n";// PEMBUAT = ROFI
			}// PEMBUAT = ROFI
			
		}// PEMBUAT = ROFI
    
    getch();// PEMBUAT = ROFI
	return 0;// PEMBUAT = ROFI
}// PEMBUAT = ROFI</p>
