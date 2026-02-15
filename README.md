# Masjid Hadi Hasan Faqeeh Website

Website resmi Masjid Hadi Hasan Faqeeh, Bogor, Indonesia.

## Fitur
- ✅ Jadwal Sholat (API Aladhan)
- ✅ Jadwal Ramadhan/Imsakiyah (API Aladhan)
- ✅ Kegiatan Masjid
- ✅ Pengumuman
- ✅ Galeri
- ✅ Bilingual (Indonesia/English)
- ✅ Dark Mode
- ✅ Responsive Design

## Teknologi
- HTML5
- TailwindCSS (CDN)
- Alpine.js (CDN)
- Aladhan API

## Deployment ke GitHub Pages

1. Push repository ke GitHub
2. Buka Settings → Pages
3. Pilih branch `main` dan folder `/ (root)`
4. Save dan tunggu beberapa menit
5. Website akan tersedia di `https://username.github.io/nama-repo/`

## Konfigurasi

### Pengaturan Ramadhan
Edit `data/settings.json`:
```json
{
  "features": {
    "ramadhanSchedule": {
      "enabled": true,    // true/false untuk on/off fitur
      "useApi": true,     // true = ambil dari API
      "hijriYear": 1447,  // Tahun Hijriah
      "hijriMonth": 9     // 9 = Ramadhan
    }
  }
}
```

### Menambah Kegiatan
Edit `data/activities.json`

### Menambah Pengumuman
Edit `data/announcements.json`

## Lisensi
© 2026 Masjid Hadi Hasan Faqeeh
