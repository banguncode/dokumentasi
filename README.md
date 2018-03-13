# dokumentasi
Diajukan guna memenuhi Tugas Pemrograman Web
Nama  : Dikna Andreana
NIM   : 5140411358

*ALGORITMA*
1) Masukkan Email
2) Masukkan Kata Sandi
3) Ulangi Langkah (1) dan (2) sampai tiga kali atau lebih
4) Pengguna diblokir

*PSEUDOCODE*
MULAI
	Input Email
	Input Kata Sandi
	if $_SESSION["salah"] >= 3
		Cetak "Maaf akun anda diblokir"
SELESAI

*FLOWCHART*

								(MULAI)
								   |
								   |
						/Input Email, Kata Sandi/
						       |
						       |									
			[Email && Kata Sandi = Salah]------<if $_SESSION["salah"] >= 3>
                   |					        Ya              |
                   |								                  |
                   |							            [Akun diblokir]
                   | Tidak								            |
                   |									                |
                   |------------------------------------
                   |
					   	(SELESAI)
