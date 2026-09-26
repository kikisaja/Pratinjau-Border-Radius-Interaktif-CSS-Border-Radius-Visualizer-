# 🎨 CSS Border-Radius Visualizer

Tool interaktif berbasis web untuk memvisualisasikan bagaimana properti `border-radius` bekerja pada CSS. Pengguna dapat mengubah kelengkungan keempat sudut secara independen melalui slider dan langsung menyalin kode CSS-nya.

Proyek ini sangat bagus untuk pemula yang ingin memahami hubungan antara **Input UI**, **Manipulasi Style CSS**, dan **Clipboard API** di JavaScript.

---

## 🎯 Konsep Pembelajaran RPL / Pemrograman Web

1. **Manipulasi Style Inline DOM:**
   Mempelajari cara mengubah properti CSS secara langsung melalui JavaScript menggunakan `element.style.borderRadius`.
2. **Event `input` (Real-time update):**
   Mendeteksi perubahan nilai slider (`<input type="range">`) secara *real-time* saat digeser menggunakan event listener `input` (bukan `change` yang hanya memicu saat dilepas).
3. **Template Literals (String Interpolation):**
   Menggabungkan variabel JavaScript ke dalam string dengan mudah menggunakan backticks (`` ` ``) dan `${variabel}`.
4. **Clipboard API (Copy Text):**
   Memanfaatkan `navigator.clipboard.writeText()` untuk membuat fitur salin (copy) teks modern yang aplikatif.

---

## 📂 Struktur Folder Proyek

```text
├── index.html       # Struktur UI aplikasi, slider, dan area output
├── style.css        # Desain Colorful Neobrutalism dan layout Grid/Flexbox
└── script.js        # Logika pembacaan slider dan manipulasi CSS
