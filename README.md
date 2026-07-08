# 🧭 OTW TUBAN — Platform Informasi Destinasi Wisata & Kuliner Khas Tuban

![Version](https://img.shields.io/badge/Version-4.1.0--Responsive-blue?style=for-the-badge)
![Engine](https://img.shields.io/badge/Engine-Tailwind__v4--Supabase-0ea5e9?style=for-the-badge&logo=tailwindcss)
![Security](https://img.shields.io/badge/Security-Route__Guard--Active-emerald-500?style=for-the-badge&logo=expressvpn)

**OTW TUBAN** adalah platform manajemen informasi geografis modern berbasis web yang menyajikan katalog destinasi wisata, situs religi bersejarah, serta warisan kuliner otentik di wilayah Kabupaten Tuban (Bumi Wali). Platform ini dirancang dengan arsitektur *Mobile-First Responsive* untuk menjamin aksesibilitas penuh di berbagai perangkat (Smartphone, Tablet, dan Desktop).

---

## 🚀 Fitur Utama

*   **Mobile-First Responsive Layout:** Antarmuka adaptif yang telah dioptimalkan secara penuh untuk perangkat layar sentuh (*mobile devices*) tanpa risiko kebocoran tata letak (*overflow layout breakdown*).
*   **Real-time Cloud Synchronization:** Sinkronisasi data terpusat menggunakan arsitektur *Backend-as-a-Service* (BaaS) dari Supabase.
*   **Secure Administration Console:** Manajemen konten (CRUD) yang dilindungi oleh sistem keamanan *Session Route Guard* terpusat melalui Supabase Auth.
*   **Holographic Error Hub:** Halaman galat (404) interaktif dengan visualisasi kompas berputar menggunakan akselerasi grafis perangkat (*hardware accelerated animation*).
*   **Animated Wilderness Night Hero:** Bagian utama beranda yang ditenagai oleh animasi gradasi warna cairan dinamis murni berbasis CSS `@keyframes`.
*   **Automatic Background Music:** Pemutar audio musik khusus halaman utama website bisa kontrol play/pause.

---

## 🛠️ Tech Stack & Integrasi

| Komponen | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Frontend Framework** | Tailwind CSS v4 CDN | Desain utilitas responsif kilat. |
| **Backend & Auth** | Supabase JS Core Engine v2 | Database relasional PostgreSQL & Manajemen Sesi. |
| **Pop-up Dialogs** | SweetAlert2 | Penanganan notifikasi umpan balik aksi premium. |
| **Typography** | Google Fonts Plus Jakarta Sans | Pengalaman membaca teks (*readability*) yang optimal. |
| **Icon Assets** | Font Awesome 6 & Icons8 | Repositori visual & ilustrasi premium. |

---

## 📂 Struktur Direktori Proyek

```text
otw-tuban/
│
├── index.html            # Halaman Utama Publik (Hero Section & Katalog)
├── 404.html              # Halaman Galat Interaktif (Kompas Lost in Space)
├── vercel.json           # Pengalihan Akses Link Acak Ke Halaman 404 (Routing Pages)
│
└── admin/
    ├── index.html        # Portal Autentikasi Kontributor (Login Page)
    └── dashboard.html    # Panel Utama Manajemen Data (CMS Console)
└── img/
    ├── ikon.png          # Ikon Utama Website (Semua Halaman)
    └── logo.png          # Logo Utama Website (Semua Halaman)
    └── background.png    # Gambar Background Hero Section (Halaman Utama)
    └── music.mp3         # Musik Otomatis Play/Pause (Halaman Utama)
