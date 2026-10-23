Matriks uji dan eksperimen kegagalan 
1.Email kosong akan ditolak karena pada program ada kode required yang membuat clien wajib mengisi
2.email abc akan ditolak karena email harus memiliki "@gmail"
3.Email contoh valid akan diterima jika lainnya valid, karena semua harus diisi termasuk email.
4.Jumlah 0/6 akan ditolak karena diprogram, kita membuat kode min="1" dimana kita harus mengisi minimal 1 dan bukan maksimal 6 pada program melainkan maks="5"
5.Jumlah 1/5 akan diterima karena dalam program kita membuat min="1" dimana kita sudah mengisi 1 dan maksimal 5
6.kode 12345 akan ditolak karena bukan 6 digit, pada kode program dibuat untuk memasukkan 6 angka, "pattern="[0-9]{6}""
7.kode 001234 akan diterima karena sudah 6 digit sesuai permintaan program
8.keyboard semua kontrol dapat dijalnkan menggunakan keyboard.

Kegunaan dari required adalah jika kosong maka program akan meminta untuk mengisi.

Validator
pada sesi 3, program saya kali ini tidak memiliki error saat memvalidasi