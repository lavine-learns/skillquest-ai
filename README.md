# SkillQuest AI

SkillQuest AI adalah landing page dan mini app interaktif untuk membantu developer atau calon Data Engineer memetakan skill, mengecek skill gap, dan menjalani quest belajar yang terstruktur untuk siap menghadapi karier remote internasional.

Tema utama dari aplikasi ini adalah: belajar tidak lagi acak, tetapi seperti game progress dengan level, XP, skill tree, dan AI assistant.

## Fitur utama

- Skill tree terstruktur untuk Data Engineering
- Sistem level dan XP untuk motivasi belajar
- Progress tracking berbasis browser localStorage
- AI assistant interaktif untuk menjawab pertanyaan seperti:
  - "Saya bingung mulai belajar dari mana"
  - "Latihan English"
  - "Jadwalkan quest"
  - "Cek progress saya"
- Simulasi karier remote dan kebutuhan komunikasi teknis
- UI modern dengan tema dark mode dan layout landing page

## Tujuan aplikasi

Aplikasi ini dibuat untuk membantu pengguna:

- memahami roadmap belajar Data Engineering
- mengetahui skill gap yang perlu ditingkatkan
- mendapatkan quest belajar yang praktis dan terukur
- meningkatkan kemampuan technical English untuk komunikasi remote
- mempersiapkan diri untuk karier Data Engineer yang siap kerja jarak jauh

## Struktur halaman

Halaman utama terdiri dari beberapa bagian utama:

1. Hero section
   - tagline: "Level Up Your Skills. Get Remote-Ready."
   - deskripsi produk
   - stat level, streak, quest selesai

2. Problem vs solution
   - menjelaskan tantangan belajar Data Engineering yang bersifat luas dan tidak terarah
   - menunjukkan pendekatan yang lebih terstruktur

3. Skill Tree
   - daftar skill seperti Foundation, Ingestion, Transformation, Orchestration, Warehousing, Streaming, Data Quality, Cloud, Remote Communication, Career Readiness
   - tiap skill memiliki level progress dan quest

4. AI Chat
   - interaksi sederhana dengan bot yang membalas pertanyaan umum
   - mode tanya jawab dan latihan English

5. CTA footer
   - mendorong pengguna untuk mulai quest

## Teknologi yang digunakan

Proyek ini merupakan aplikasi frontend statis berbasis HTML, CSS, dan JavaScript murni tanpa framework.

- HTML
- CSS
- JavaScript

## Cara menjalankan

Karena ini adalah app statis, Anda tidak perlu build tool atau dependency install.

### Opsi 1: buka langsung di browser

- buka file [index.html](index.html) di browser

### Opsi 2: jalankan server lokal

```bash
cd /workspaces/skillquest-ai
python3 -m http.server 8000
```

Lalu buka:

```bash
http://localhost:8000
```

## Folder project

```text
skillquest-ai/
├── index.html
├── README.md
└── .gitignore (jika ada)
```

## Catatan penting

- Progress disimpan di browser menggunakan localStorage.
- Data bersifat lokal dan tidak dikirim ke server.
- Aplikasi ini bersifat showcase / prototype interaktif, bukan produk backend yang lengkap.

## Customization

Anda dapat menyesuaikan beberapa bagian berikut di [index.html](index.html):

- link LinkedIn di bagian footer
- skill tree dan quest
- level awal dan progress default
- prompt AI assistant dan pesan chat
- warna tema serta branding

## Lisensi

Proyek ini dibuat untuk kebutuhan showcase/personal project dan dapat disesuaikan sesuai kebutuhan Anda.

## Ringkasan singkat

SkillQuest AI adalah pengalaman belajar berbasis game yang mengubah pembelajaran Data Engineering menjadi roadmap yang terarah, lebih menyenangkan, dan siap dipakai untuk profil karier remote.
