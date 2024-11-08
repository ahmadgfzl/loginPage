Blackbox Testing untuk Fitur Login
Blackbox testing menguji aplikasi dari perspektif pengguna. Berikut adalah beberapa skenario pengujian login.

Skenario 1 - Login Berhasil

Langkah: Masukkan email dan password yang benar.
Ekspektasi: Pengguna berhasil login dan diarahkan ke halaman dashboard.
Skenario 2 - Email Tidak Terdaftar

Langkah: Masukkan email yang tidak terdaftar dan password acak.
Ekspektasi: Muncul pesan "Email atau password salah."
Skenario 3 - Password Salah

Langkah: Masukkan email yang benar tetapi password salah.
Ekspektasi: Muncul pesan "Email atau password salah."
Skenario 4 - Email Tidak Valid

Langkah: Masukkan email dalam format yang salah (contoh: email@com).
Ekspektasi: Muncul pesan validasi bahwa format email tidak valid.
Skenario 5 - Password Kurang dari 6 Karakter

Langkah: Masukkan password dengan kurang dari 6 karakter.
Ekspektasi: Muncul pesan validasi bahwa password minimal harus 6 karakter.
