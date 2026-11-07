 Day 1 - Plants vs Zombies

 Nama Peserta
Muhammad Luthfi Fauzi Imani

 Deskripsi Repository
Repository ini aku buat untuk menyimpan hasil dan catatan dari workshop "Building with AI, Managing Change with GitHub". Isinya proyek Plants vs Zombies yang aku kerjakan dengan bantuan AI, lalu aku kelola pakai Git dan GitHub.

 Tujuan Repository
- Latihan memakai Git dan GitHub dari awal.
- Menyimpan dokumentasi dan hasil belajar dari workshop.
- Jadi catatan buat aku sendiri kalau nanti lupa alurnya.

 Kegiatan Workshop yang Didokumentasikan
Judul: Building with AI, Managing Change with GitHub
Pemateri: Nugi Farhan (Senior Product Designer)

 Rangkuman Materi Workshop
Di workshop ini ada dua bagian besar. Bagian pertama tentang prompt engineering, yaitu cara menulis perintah ke AI supaya hasilnya sesuai yang kita mau. Prompt yang bagus punya empat unsur: Role, Task, Context, dan Format. Contohnya, menulis "Create student task planner" saja hasilnya akan umum, tapi kalau dijelaskan tujuan, kebutuhan, dan batasannya, hasilnya jauh lebih pas.

Bagian kedua tentang Git dan GitHub. Git itu alat di komputer untuk mencatat perubahan file, sedangkan GitHub itu tempat menyimpannya secara online supaya bisa dibagikan dan dikerjakan bareng. Kami juga belajar alur kerja Git: file diubah di working directory, dimasukkan ke staging area, lalu disimpan lewat commit. Setelah itu baru dikirim ke GitHub dengan push.

Sebelum praktik, kami menyiapkan semuanya dulu: install Git, atur nama dan email, install VS Code, dan bikin SSH key supaya komputer bisa terhubung ke GitHub.

 Poin Penting dan Pengetahuan Baru
- Prompt yang detail bikin hasil AI jauh lebih bagus daripada prompt yang singkat.
- Git dan GitHub ternyata dua hal yang berbeda. Dulu aku kira sama.
- Perubahan tidak langsung tersimpan. Harus `git add` dulu, baru `git commit`, baru `git push`.
- SSH key itu ada dua: public key (boleh dikasih ke GitHub) dan private key (jangan dibagikan ke siapa pun).
- Perintah `ssh -T git@github.com` berguna untuk mengecek koneksi ke GitHub sudah berhasil atau belum.
- Terminal ternyata tidak semenakutkan yang aku bayangkan.

 Pendapat Pribadi tentang Day 1 Proyek Workshop
Jujur, Day 1 ini seru tapi lumayan bikin pusing di awal. Bagian yang paling bikin bingung buat aku adalah setup SSH key. Sempat salah ketik perintah, lalu koneksinya ditolak dengan pesan "Permission denied (publickey)" karena key-nya belum aku tambahkan ke GitHub. Waktu mengisi README pun aku sempat salah paste, jadi isinya malah perintah terminal. Tapi setelah dicoba lagi pelan-pelan, akhirnya berhasil, dan rasanya lega banget waktu muncul tulisan "successfully authenticated".

Dari sini aku sadar kalau error itu normal dan biasanya ada penyebab yang jelas. Aku jadi lebih paham alur Git dan lebih percaya diri membuka terminal. Ke depannya aku mau lebih rajin commit dan push, dan belajar menulis prompt AI yang lebih jelas.
