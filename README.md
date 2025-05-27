# Storybook Practicum (prak4)

# Nama :
Hamdan Dzulfikar Makarim

# Deskripsi Proyek :
Proyek Flutter ini adalah sebuah Petualangan Antariksa berbasis interaktif yang mengajak pengguna mengikuti cerita seorang astronot dalam misi membuka box misterius di luar angkasa. Pengguna dapat berinteraksi langsung dengan elemen-elemen di layar menggunakan gesture seperti drag, tap, double tap, dan long press untuk menyelesaikan misi.

# ScreenShots Emulator :

1. **Title Page**  
   Halaman pembuka dengan judul cerita dan tombol mulai.

   ![Title Page](Prak%204/web1.png)

2. **Scene Page**  
   Halaman interaktif dengan astronaut, peti, dan kunci yang bisa didrag.

   ![Scene Page](Prak%204/web2.png)
   ![Scene Page](Prak%204/web3.png)

3. **End Page**  
   Halaman akhir yang menampilkan pesan petualangan selesai dan tombol mulai ulang.

   ![End Page](Prak%204/web4.png)


# Penjelasan Program:

- Title Page
Halaman pembuka yang menampilkan judul "Petualangan Antariksa" beserta sebuah tombol untuk memulai cerita. Saat tombol ditekan, pengguna akan diarahkan ke halaman adegan interaktif.

- Interactive Scene Page
Merupakan inti dari aplikasi ini, di mana pengguna dapat berinteraksi secara langsung melalui beberapa gesture, antara lain:

* - Double Tap pada karakter astronot 👩‍🚀 untuk menampilkan dialog percakapan.

* - Long Press pada ikon peti 📦 untuk melihat petunjuk yang mengarah pada misi.

* - Drag kunci 🔑 ke arah peti. Jika posisi kunci tepat di atas peti, maka peti akan terbuka 🔓 dan cerita akan berlanjut ke halaman berikutnya.

* - Geser latar belakang menggunakan gesture drag untuk menciptakan efek visual seperti parallax menggunakan RawGestureDetector.

- End Page
Halaman penutup yang muncul setelah misi berhasil diselesaikan. Halaman ini menyampaikan ucapan selamat 🎉 dan menyediakan tombol untuk memulai kembali cerita dari awal.

# Cara Menjalankan Aplikasi:
flutter pub get, lalu flutter run