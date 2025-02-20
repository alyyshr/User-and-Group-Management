Manajemen user dan grup merupakan bagian penting dari pemeliharaan keamanan sebuah sistem. Menejemen user dan grup dapat dikategorikan dalam dua jenis:
1.	Pengaturan root dan user      
      Sistem operasi Linux ataupun Unix-like dirancang sebagai sistem dengan multi-user. Dimana setiap user akan memiliki mekanisme pemisahan dan perlindungan file dari setiap user individual dan memungkinkan setiap user menggunakan sistem secara simultan. Setiap akun user akan mendapatkan nomor indentifikasi secara otomatis. Nomor ini disebut dengan User ID (UID).    
    	Root merupakan akun definitif dari sistem administratif yang memungkinkan melakukan semua perintah dan file pada sistem operasi linux atau Unix-like. Root dapat berupa akun root, root user dan superuser. Seperti halnya akun reguler, root memiliki direktori home pada sistem yang disebut sebagai top level directory. Di dalam directory root terdapat subdirectory dan file-file yang dibutuhkan. Direktori root dilambangkan dengan notasi forward slash (/) atau disebut juga dengan slash-root. Akun root memiliki privileges yang memberikan kekuasaan sepenuhnya terhadap sistem yang bersifat absolut. Hak akun root memungkinkannya untuk mengubah sistem ataupun mengubah hak akses atas sistem untuk user lain.    
    	Untuk melakukan fungsi root, anda akan diperkenalkan dengan perintah sudo. Sudo ( su “do”) memungkinkan administrator sistem untuk mendelegasikan hak akses pada user tertentu atau sekelompok grup tertentu untuk menjalankan beberapa atau seluru perintah sebagai root atau sebagai user lain namun tetap memberikan jejak audit dari perintah tersebut dan argument yang diberikan. Pengaturan sudo dilakukan pada file sudoer sebagai file setup. File sudoer hanya diberikan akses pengubahan dan pembacaannya pada akun root. Pengubahan konten pada file sudoer hanya diijinkan menggunakan perintah visudo.      
    	Selain akun root, sistem operasi Linux memungkinkan adanya user lain dengan menejemen yang terpisah dan saling bebas satu sama lain. Masing-masing akun user selain root dapat mememiliki privilege yang berbeda. Pengaturan akun dilakukan menggunakan akun root atau superuser. Menejemen user yang dapat dilakukan meliputi penambahan akun user, penghapusan akun user, pengubahan password secara permanen maupun berkala, penambahan atau pengurangan hak akses atas file atau folder. Juga dapat melakukan pengaturan secara berkelompok yang disebut grup.

2. File Permission
      Dalam Linux dan unix, semua direpresentasikan dalam file. Semua file ini memiliki permission sistem yang memungkinkan atau mencegah user lain melihat, mengubah atau mengeksekusi file tersebut. Kemampuan mengubah ini dimiliki oleh akun root atau superuser. Untuk mengatur permission, terdapat tiga tipe pembatasan akses, yaitu:
   ![image](https://github.com/user-attachments/assets/b57b384e-de79-4197-8da1-7c569ac33961)

   Untuk mengubah permission, dapat menggunakan perintah chmod dengan sintaks -> chmod (option) filename
   ![image](https://github.com/user-attachments/assets/3ec10c0c-df7c-4d2b-b2c1-6b3ec7fc270e)

**Perintah yang digunakan untuk menejemen user**  
![image](https://github.com/user-attachments/assets/0e58dbd6-5476-4b9a-b18d-baa3d4e673e9) 



