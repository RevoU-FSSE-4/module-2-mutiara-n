# deploy-project
Contoh deploy netlify

# Best Furiends Furever
This is a simple animal shelter for cat adoption website.

## About Project
This website consist of three sections. In the first section, there's a preview of some cats that are ready for adoption. The second section has an "About Us" page which will be filled with short information about the animal shelter. The last section contains a "Contact Us" for user who might be interest in adopting a cat or two from the website.

## Website Preview
![header](images/header.png)
![section](images/section-1.png)
![section](images/section-2.png)
![section](images/section-3.png)

## Deployment Process
1. Daftarkan akun netlify menggunakan github serta emberi izin bagi netlify untuk mengakses akun github.
![deploy](deployment/deploy1.png)
![deploy](deployment/deploy2.png)
![deploy](deployment/deploy3.png)

2. Setelah akun netlify berhasil dibuat, kita akan membuat situs berdasarkan project yang sudah ada. Dikarenakan netlify sudah terhubung dengan akun github, repositori yang sudah ada dapat digunakan dalam pembuatan situs.
![deploy](deployment/deploy4.png)
![deploy](deployment/deploy5.png)

3. Pilih salah satu repositori yang akan di deploy, lalu isi site name serta pilih branch mana yang akan di deploy.
![deploy](deployment/deploy6.png)
![deploy](deployment/deploy7.png)
![deploy](deployment/deploy8.png)

4. Tunggu beberapa saat sampai situs selesai di deploy dan menampilkan halaman berikut.
![deploy](deployment/deploy9.png)

5. Setelah situs selesai di deploy, langkah selanjutnya adalah melakukan set up untuk custom domain. Domain yang digunakan untuk project ini adalah Niagahoster. Pertama-tama, cari nama domain yang diinginkan dan pilih paket domain yang diinginkan.\
![deploy](deployment/deploy10.png)
![deploy](deployment/deploy11.png)


6. Pilih durasi paket yang dibutuhkan, kemudian pilih metode pembayaran paket domain.
![deploy](deployment/deploy12.png)
![deploy](deployment/deploy13.png)

7. Jika pembayaran telah selesai dilakukan, niagahoster akan menunjukkan bukti bahwa pembayaran telah berhasil.
![deploy](deployment/deploy14.png)

8. Lakukan registrasi domain dengan mengisi data diri, maka registrasi domain selesai dilakukan dan set up custom domain dapat dimulai.
![deploy](deployment/deploy15.png)
![deploy](deployment/deploy16.png)

9. Pilih menu Domain Management pada situs Netlify yang telah di deploy, kemudian pilih Add Domain.
![deploy](deployment/deploy17.png)

10. Tambahkan custom domain sesuai dengan domain yang telah didaftarkan.
![deploy](deployment/deploy18.png)
![deploy](deployment/deploy19.png)

11. Dapat dilihat dari gambar sebelumnya, situs belum bisa berjalan tanpa DNS. Setup DNS dapat dilakukan di niagahoster dengan mengganti <b>nameservers</b> di halaman domain overview dengan nameservers Netlify.
![deploy](deployment/deploy21.png)
![deploy](deployment/deploy22.png)
![deploy](deployment/deploy23.png)
![deploy](deployment/deploy24.png)

12. Tunggu maksimal 24 jam sampai tanda Awaiting External DNS berubah menjadi Netlify DNS, maka proses penambahan custom domain selesai dilakukan.\
![deploy](deployment/deploy19.png)
![deploy](deployment/deploy25.png)