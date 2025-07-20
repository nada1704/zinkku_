# 🚀 ZINKKU ONLINE - Deployment Guide

## 📱 Website Monitoring Zinc untuk Balita

Website ini telah siap untuk diakses publik dengan fitur lengkap monitoring zinc untuk balita.

## 🎯 Fitur Utama
- ✅ Monitoring harian zinc untuk balita
- ✅ Sistem login dual role (orang tua & petugas)
- ✅ Dashboard petugas dengan data monitoring
- ✅ WhatsApp reminder untuk orang tua
- ✅ Informasi edukasi lengkap tentang zinc

## 🚀 Cara Deploy ke Publik

### **Opsi 1: Deploy ke Vercel (Rekomendasi)**
1. **Fork repository** ini ke GitHub Anda
2. **Login ke Vercel**: https://vercel.com
3. **Import project** dari GitHub
4. **Deploy otomatis** - tidak perlu konfigurasi tambahan

### **Opsi 2: Deploy ke Netlify**
1. **Build project**:
   ```bash
   npm run build
   npm run export
   ```
2. **Upload folder `out`** ke Netlify

### **Opsi 3: Deploy ke GitHub Pages**
1. **Build project**:
   ```bash
   npm run build
   npm run export
   ```
2. **Upload folder `out`** ke GitHub Pages

## 📋 Prasyarat
- Node.js 18+ atau 20+
- npm atau yarn
- Browser modern (Chrome, Firefox, Safari, Edge)

## 🔧 Konfigurasi yang Sudah Siap
- ✅ Next.js dengan static export
- ✅ Optimasi untuk production
- ✅ Responsive design
- ✅ Cross-browser compatible
- ✅ WhatsApp integration siap

## 📊 Cara Menggunakan

### **Untuk Orang Tua:**
1. Buka website
2. Pilih "Orang Tua" → Registrasi dengan data anak
3. Isi formulir harian monitoring
4. Dapat pengingat otomatis via WhatsApp

### **Untuk Petugas Kesehatan:**
1. Pilih "Petugas" → Login dengan ID
2. Lihat dashboard monitoring semua pasien
3. Kirim reminder WhatsApp untuk yang terlambat
4. Export data untuk laporan

## 📱 Akses WhatsApp
- **Nomor Dokter**: +62 852-4898-0734
- **Format Nomor**: +628xxxxxxxxx (otomatis terhubung)

## 🌐 URL yang Tersedia
- **Homepage**: `/`
- **Dashboard Orang Tua**: `/parent`
- **Dashboard Petugas**: `/healthcare`
- **Info Zinc**: `/info/zinc-benefits`, `/info/zinc-usage`, `/info/zinc-dosage`, `/info/oralit`

## 🚀 Langkah Deploy Cepat

### **Deploy ke Vercel (1 Klik)**
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/username/zinkku-online)

### **Deploy ke Netlify**
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/username/zinkku-online)

## 📞 Support
Untuk bantuan deployment, hubungi:
- WhatsApp: +62 852-4898-0734
- Email: support@zinkku-online.com

## 🎉 Website Siap untuk Publik!
Website monitoring zinc untuk balita sekarang siap untuk diakses oleh publik dengan deployment yang mudah ke berbagai platform hosting.
