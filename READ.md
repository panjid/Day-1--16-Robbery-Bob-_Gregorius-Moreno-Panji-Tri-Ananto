* Nama Lengkap: Gregorius Moreno Panji Tri Ananto
* Kegiatan: Day 1 - Workshop Building with AI & Managing Change with GitHub

---

## Deskripsi & Tujuan Repository

Repository ini berstatus Public dan berfungsi sebagai dokumentasi resmi kegiatan Workshop Day 1. Repository ini memuat rangkuman materi Prompt Engineering, dasar-dasar Git & GitHub, alur kerja (workflow), serta perintah-perintah terminal utama yang dipelajari selama sesi workshop berlangsung.

---

## Catatan Pembelajaran: Building with AI & Managing Change with GitHub

Pemateri: Nugi Farhan (Senior Product Designer)

### 1. Prompt Engineering Fundamentals

Prompting adalah seni merancang instruksi agar AI memberikan hasil yang presisi dan relevan.

Struktur 4 Elemen Prompt Efektif:

1. Role: Peran yang harus diambil AI (misal: Senior Web Developer).
2. Task: Perintah atau tujuan utama secara spesifik.
3. Context: Kebutuhan (requirements) dan batasan (constraints).
4. Format: Bentuk luaran (output) yang diharapkan (misal: kode lengkap + penjelasan).

Taktik Utama Prompting:

* Gunakan kata kerja aksi (action verbs).
* Tentukan target audiens, format, dan batasan panjang luaran.
* Sertakan data/fakta pendukung dan definisikan istilah kunci.

---

### 2. Memahami Git vs GitHub

| Komponen | Deskripsi Utama |
| --- | --- |
| Git | Distributed Version Control System (DVCS) lokal untuk melacak riwayat perubahan file kode. |
| GitHub | Platform cloud berbasis web untuk menyimpan repository Git online, memfasilitasi kolaborasi, dan integrasi CI/CD. |

3 Area Kerja Git (Git Workflow):

1. Working Directory: Area tempat kita mengubah file kode di komputer lokal.
2. Staging Area: Area penampungan (git add) untuk memilih perubahan yang siap di-commit.
3. .git directory (Repository): Database tempat riwayat perubahan tersimpan secara permanen (git commit).

---

### 3. Cheat Sheet Command Utama

Initial Setup & Identitas:
git --version
git config --global user.name "Gregorius Moreno Panji Tri Ananto"
git config --global user.email "email-anda@example.com"

Basic Git Workflow:
git init
git add .
git commit -m "Feat: Add initial task planner structure"

GitHub Integration & Push:
git remote add origin <URL_REPOSITORY_GITHUB>
git push origin main
git pull origin main
git clone <URL_REPOSITORY>

Setup SSH Key (macOS Quick Ref):
ssh-keygen -t ed25519 -C "email-anda@example.com"
eval "$(ssh-agent -s)"
pbcopy < ~/.ssh/id_ed25519.pub
ssh -T git@github.com

---

## Pendapat Pribadi (Day 1 Workshop)

Sesi Day 1 memberikan wawasan yang sangat praktis, terutama dalam mengombinasikan AI-assisted development dengan version control menggunakan Git. Pemisahan antara konsep dasar prompting yang terstruktur dengan alur kerja Git/GitHub membantu memperjelas bagaimana cara mengelola proyek perangkat lunak modern secara lebih efisien dan terorganisir.