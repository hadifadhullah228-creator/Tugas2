# Tugas2



1. Ubahlah informasi finger pada komputer Anda.
   <img width="1280" height="800" alt="t2 1" src="https://github.com/user-attachments/assets/fec472f0-4956-4465-84a4-e6f440784184" />

2. Lihatlah user-user yang sedang aktif pada komputer Anda.
   <img width="1280" height="800" alt="t2 2" src="https://github.com/user-attachments/assets/ee970777-000b-4f81-95f8-2cf2d190c369" />

3. Buka file $cat /etc/group kemudian analisa untuk root:x
   <img width="1280" height="800" alt="t2 3" src="https://github.com/user-attachments/assets/920c6bed-0577-415f-b98a-de9b6cc418cd" />

   Hasil Analisa
   
a. root : Menunjukkan nama grup (group name), yaitu grup 
administrator tertinggi pada sistem Linux

b. x : Menandakan keberadaan password grup yang telah dienkripsi 
dan disimpan secara aman di dalam file terpisah (/etc/gshadow) 

c. 0 : Menunjukkan GID (Group ID) atau nomor identifikasi unik untuk 
grup tersebut, di mana angka 0 secara khusus dicadangkan untuk 
tingkat akses tertinggi (root)

d. Bagian akhir yang kosong (:) : Menunjukkan daftar anggota 
tambahan di dalam grup tersebut. Karena dikosongkan, artinya tidak 
ada user sekunder lain yang tergabung secara manual di baris ini 
(pemilik utamanya adalah akun root itu sendiri)


