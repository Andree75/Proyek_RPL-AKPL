**Modul Autentikasi pengguna**

  --> Login (End-user, Admin)
  
      --> Email
      --> password
      --> Link untuk Register (jika belum punya akun)
      
  --> Register (End-User, Admin)
  
      --> Username
      --> E-mail
      --> Password
      --> Konfirmasi Password
      
  --> Reset password (End-User, Admin)
  
      --> Email
      --> Cek link pemulihan di Gmail
      --> password baru
      --> konfirmasi password baru

**Modul Main/Utama**

  --> Dashboard Utama

  --> Halaman Pengelolaan Paket Wisata (Admin, Travel Manager,Agent)
      Tabel CRUD Paket Wisata
      
          --> Buat Paket
              --> tipe paket
              --> Nama daerah Paket
              --> durasi inap
              --> Nominal Harga
              --> Fasilitas tersedia
              --> Destinasi Wisata
          --> Edit Paket
          --> Hapus Paket
      
      --> (function) Atur Kuota per-tanggal/Batch dari paket wisata-nya

  --> Halaman pencarian(searching/filter) (End-User)

      --> sort by Destinasi wisata
      --> sort by durasi dari Paket wisata
      --> sort by tanggal keberangkatan
      --> sort by range harga (terendah/tertinggi)
      --> jika klik paket/destinasi maka akan memunculkan rincian detail dari yang dipilih tersebut

      
  --> Halaman Booking/Reservasi (End-User)
    Tabel CRUD Reservasi
    
      --> Buat Reservasi
          --> Pilih Tipe paket wisata
          --> pilih Daerah tujuan
          --> pilih durasi inap
      --> Edit Reservasi
      --> Hapus Reservasi

  --> Halaman Payment (End-user)
      
      --> Pilih metode pembayaran
      --> Masukkan Nominal biaya
      --> Output ditampilkan

  --> Halaman Pembatalan reservasi

  
