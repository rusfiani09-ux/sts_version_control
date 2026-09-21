# TUGAS CONTROL VERSION - JAWABAN STS

**Nama:** Melynda Putri Rusfiani
**Kelas:** XII PPLG 1

---

### 1. Apa yang dimaksud dengan GitHub?
**Jawaban:**
GitHub adalah platform berbasis web (cloud) yang digunakan sebagai repositori untuk menyimpan, mengelola, serta melacak perubahan kode sumber (source code) proyek perangkat lunak.

### 2. Apa Fitur dan Komponen Utama GitHub?
**Jawaban:**
Berdasarkan standar pengembangan perangkat lunak modern, fitur dan komponen utama GitHub meliputi:
* **Repositories (Repo):** Tempat atau folder digital untuk menyimpan seluruh file proyek dan riwayat perubahannya.
* **Branches:** Cabang kode yang digunakan untuk mengembangkan fitur baru secara terisolasi tanpa mengganggu kode utama (branch `main`).
* **Commits:** Catatan riwayat yang merekam setiap perubahan kode yang dilakukan oleh pengembang beserta pesan penjelasannya.
* **Pull Requests (PR):** Fitur untuk meninjau, mendiskusikan, dan menggabungkan (*merge*) perubahan kode dari satu branch ke branch lainnya.
* **Issues:** Sistem pelacakan bug, tugas, dan diskusi proyek.
* **GitHub Actions:** Fitur untuk otomatisasi pengujian dan penyebaran aplikasi (*Continuous Integration/Continuous Deployment* atau CI/CD).

### 3. Sebutkan Alur Utama (GitHub Workflow)?
**Jawaban:**
Alur kerja standar GitHub (GitHub Workflow) terdiri dari langkah-langkah sistematis berikut:
1. **Create a Branch:** Membuat cabang baru dari branch utama (`main`) untuk mulai mengerjakan fitur atau perbaikan tertentu.
2. **Make Changes (Commit):** Melakukan modifikasi kode pada branch tersebut dan menyimpannya menggunakan perintah *commit* secara berkala.
3. **Open a Pull Request (PR):** Mengajukan permohonan penggabungan kode agar anggota tim lain dapat meninjau (*review*) kualitas kode yang dibuat.
4. **Discuss and Review:** Proses diskusi, pengujian otomatis, dan revisi kode jika ditemukan adanya *bug* atau ketidaksesuaian.
5. **Merge:** Setelah disetujui, kode dari branch fitur digabungkan secara permanen ke branch utama (`main`).
6. **Delete Branch:** Menghapus branch fitur yang sudah digabungkan agar repositori tetap bersih dan rapi.

### 4. Apa keuntungan utama dari pembatasan branch main?
**Jawaban:**
Menurut praktik terbaik (*best practices*) dalam rekayasa perangkat lunak, keuntungan utama menerapkan pembatasan (*branch protection rules*) pada branch `main` adalah:
* **Menjaga Stabilitas Kode Utama:** Mencegah pengembang melakukan *push* kode secara langsung yang belum diuji, sehingga branch `main` selalu dalam kondisi siap rilis (*production-ready*).
* **Menjamin Kualitas melalui Code Review:** Mewajibkan adanya proses peninjauan (*pull request*) dan persetujuan minimal dari pengembang lain sebelum kode digabungkan.
* **Mencegah Kerusakan yang Tidak Disengaja:** Menghindari terhapusnya branch utama atau adanya perubahan riwayat *commit* (*force push*) yang dapat merusak kolaborasi tim.
*
