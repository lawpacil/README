# Tugas Akhir Kelompok - LAW 2024
MVP Produk Layanan Aplikasi Web

## Deskripsi Singkat

Dalam tugas kali ini, para mahasiswa (secara berkelompok 4 mahasiswa per kelompok)
diminta untuk membuat produk/sistem (tema bebas) dengan arsitektur web service dan
mengikuti kriteria-kriteria yang sebagai berikut.

## Kriteria

- [ ] 1. Memiliki fungsionalitas sistem yang lengkap
- [ ] 2. Memiliki mekanisme authentikasi pengguna layanan
- [ ] 3. Menerapkan sistem authentikasi untuk setiap layanan yang terlibat di dalamnya.
- [ ] 4. Memiliki dokumentasi yang benar & rapih. Misalkan: untuk akses suatu endpoint dibutuhkan param apa saja, contoh response-nya, skenario kemungkinannya seperti apa saja, jika error dibedakan melalui status codes dan message yang jelas.
- [ ] 5. Memiliki minimal satu synchronous service.
- [ ] 6. Memiliki minimal satu asynchronous service (boleh menggunakan MQ).
- [ ] 7. Memiliki satu layanan yang menerapkan contingency service (boleh menggunakan semacam load balancer yang sudah ada).
- [ ] 8. Memiliki beberapa service yang di-deploy pada VM/container terpisah.
- [ ] 9. Memiliki minimal satu service yang merupakan choreography / orchestration atas beberapa service di belakangnya
- [ ] 10. Memiliki minimal satu buah service yang memiliki frontend untuk:
  - [ ] Dapat menjadi pintu masuk untuk memberikan argumen ke dalam sistem
  - [ ] Dapat menampilkan daftar proses yang sedang berjalan “di belakang”
  - [ ] Dapat menunjukkan status progress proses secara real time
  - [ ] Dapat menampilkan/mendownload hasil proses
- [ ] 11. Minimal menggunakan dua bahasa pemrograman pada backend.
- [ ] 12. Minimal menggunakan dua database pada backend.
- [ ] 13. Memiliki log sentral untuk melihat seluruh log dari microservices yang ada (opsional)
