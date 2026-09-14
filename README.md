# Learning Buddy

**Learning Buddy** adalah platform belajar yang membantu pengguna (khususnya calon *developer*) menemukan learning path yang tepat, memantau progres belajar, dan mendapatkan bantuan personal lewat AI Chatbot menggunakan LLM Gemini (Google) lengkap dengan fitur deteksi *job role* berbasis skill assessment.

> Repo ini hanya berisi kumpulan desain produk dan video testing.

## ✨ Fitur Utama

### 1. Homepage & Learning Path
Menampilkan pilihan *learning path* (AI Engineer, Android Developer, Back-End Developer JavaScript/Python, Data Scientist, dsb.) lengkap dengan daftar *course* dan roadmap belajar terstruktur per path.

### 2. Autentikasi (Login & Register)
Alur masuk/daftar akun sederhana sebagai pintu masuk ke dashboard belajar pengguna.

### 3. Dashboard Pengguna
Ringkasan progres belajar secara real-time: success rate, jam belajar, persentase penyelesaian, daftar kursus yang sedang diambil, kalender jadwal, aktivitas mingguan, upcoming tasks, hingga *AI insights* atas performa belajar pengguna.

### 4. Personal Learning Assistant (Chatbot)
AI chatbot menggunakan LLM Gemini yang menyapa pengguna secara personal dan bisa menjawab pertanyaan seperti:
- Skill apa yang sudah berkembang?
- Buatkan strategi belajar untuk saya
- Tampilkan weekly study plan saya
- Tampilkan roadmap belajar saya

Chatbot juga bisa menyajikan roadmap yang diperbarui otomatis berdasarkan progres (status *Completed / In Progress / Locked* per modul).

### 5. Deteksi Job Role & Skill Assessment
Fitur untuk membantu pengguna menemukan *job role* yang cocok berdasarkan minat/preferensi, lalu menguji kemampuan lewat assessment pilihan ganda (18 soal). Hasilnya berupa level kemampuan keseluruhan (Beginner/Intermediate/dst) beserta breakdown skor per skill, dan rekomendasi course lanjutan.
