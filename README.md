# Apa itu berLayar – Berbagi Layar Secara Lokal??

**berLayar** adalah aplikasi ringan untuk berbagi tampilan layar komputer Anda secara **lokal** ke perangkat lain melalui browser, tanpa perlu koneksi internet atau instalasi tambahan di sisi penerima.

Aplikasi ini berjalan secara **offline** di jaringan lokal (LAN/WiFi), dan dapat diakses melalui browser seperti Google Chrome, Edge, Firefox, atau Safari dari perangkat lain (laptop, tablet, atau ponsel).

---

## Fitur

- **Streaming langsung** tampilan layar Anda ke perangkat lain
- **Akses melalui browser** — tidak perlu instal di client
- **Tidak butuh internet**, cukup berada di jaringan yang sama
- **Bisa dikustomisasi** (logo, teks, dan tampilan halaman)
- Privasi terjaga karena hanya berjalan di jaringan lokal Anda

## Produk berLayar

### 1) Lite Edition (Windows)
- **Tanpa GUI** (berjalan di console).
- Hanya membagikan layar utama.
- Tidak ada pilihan monitor, FPS, kualitas, kamera, atau kustomisasi.
- **Menghentikan:** tutup jendela console.
- Cocok untuk **PC/laptop low-end** dan penggunaan cepat.

### 2) Pro Edition (Windows)
- **GUI Admin Panel** lengkap.
- Pilih monitor, atur FPS/kualitas/skala.
- **Kamera PiP** (posisi/ukuran/opacity).
- **Pratinjau** sebelum berbagi layar (toggle).
- Tema gelap/terang & ukuran font.
- Info **IP:PORT** & **timer durasi**.
- Kustomisasi tampilan viewer (`index.html`, logo, dsb.).
- **Stop** via GUI atau dengan menutup console.

### 3) Exclusive Build — Platform Edition (macOS/Linux)
- Build **khusus** untuk **macOS**/**Linux** (non-publik; by request).
- **Fitur setara Pro Edition**, disesuaikan dengan platform target.
- Proses integrasi/penyesuaian dilakukan secara manual.

> **Catatan:** **Pro Edition** dan **Exclusive Build (Platform Edition)** memiliki **fitur yang sama**. Perbedaannya hanya **platform** (Windows vs macOS/Linux) dan **model distribusi** (publik vs khusus).

---

## Spesifikasi Sistem

> Fokus utama rilis publik saat ini adalah **Windows**. Paket Exclusive Build melayani macOS/Linux secara khusus (non-publik).

| Paket | OS | CPU Minimal | RAM | Display | Jaringan | Catatan |
|------|----|-------------|-----|---------|----------|---------|
| **Lite** | Windows 10/11 (64-bit) | Dual-core i3 gen4 / setara | 2 GB (disarankan 4 GB) | 1366×768 | Wi-Fi 4 / LAN | Tidak perlu kamera |
| **Pro** | Windows 10/11 (64-bit) | Dual-core i3 gen6 / Ryzen 3 | 4 GB (disarankan 8 GB) | 1920×1080 | Wi-Fi 5/6 / LAN Gigabit | **Kamera diperlukan** |
| **Exclusive Build** | macOS / Linux | Setara Pro | Sesuai OS | Sesuai OS | Sesuai OS | Integrasi manual; fitur setara Pro |

---
## 📊 Perbandingan Fitur — Lite vs Pro

> **Pro** dan **Exclusive Build** setara fitur. Untuk paket **Exclusive Build**, rujuk kolom **Pro**.
<svg xmlns="http://www.w3.org/2000/svg" style="display:none;">
  <symbol id="icon-check" viewBox="0 0 24 24">
    <path fill="#12B886" d="M9 16.2l-3.5-3.5-1.4 1.4L9 19 20.3 7.7l-1.4-1.4z"/>
  </symbol>
  <symbol id="icon-cross" viewBox="0 0 24 24">
    <path fill="#FA5252" d="M18.3 5.7l-1.4-1.4L12 9.2 7.1 4.3 5.7 5.7 10.6 10.6 5.7 15.5l1.4 1.4L12 12 16.9 16.9l1.4-1.4-4.9-4.9z"/>
  </symbol>
</svg>

<table>
  <thead>
    <tr>
      <th style="text-align:left;">Fitur</th>
      <th style="text-align:center;">Lite</th>
      <th style="text-align:center;">Pro</th>
    </tr>
  </thead>
  <tbody>
    <!-- Fitur dasar (ada di semua edisi) -->
    <tr>
      <td>Jalankan dengan double-click</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Streaming layar utama</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Menghentikan stream dengan tutup console</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>

    <!-- Fitur Pro-only -->
    <tr>
      <td>GUI Admin Panel</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Pilih monitor yang ingin dibagikan</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Atur FPS (5–30)</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Atur kualitas JPEG (30–100)</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Atur skala ukuran layar (50–100%)</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Integrasi kamera (PiP)</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Atur posisi/ukuran/opacity kamera</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Tema gelap/terang & ukuran font UI</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Pratinjau sebelum berbagi layar</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Timer durasi sesi</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Kustomisasi <code>index.html</code> & logo viewer</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
    <tr>
      <td>Menghentikan stream lewat GUI</td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Tidak"><use href="#icon-cross"/></svg></td>
      <td style="text-align:center;"><svg width="18" height="18" role="img" aria-label="Ya"><use href="#icon-check"/></svg></td>
    </tr>
  </tbody>
</table>

---

## Tampilan
**Console — Lite Edition**  
![Console Lite](docs/images/console-lite.png)

**GUI — Pro Edition (Dark)**  
![GUI Pro](docs/images/gui-pro-dark.png)

**Viewer — Browser Client**  
![Viewer Client](docs/images/viewer-client.png)

---

## Cara Menggunakan

### Lite Edition

1. **Jalankan file `berLayar.exe`**  
   (cukup klik dua kali)

2. Setelah terbuka, aplikasi akan menampilkan alamat IP lokal seperti:
   ```bash
    Akses aplikasi dari web browser dan masukkan URL:
    192.168.1.10:2025 (ini hanya contoh, IP akan menyesuaikan dengan subnet router/jaringan Anda)

3. **Buka browser di perangkat lain** (yang terhubung ke jaringan WiFi/LAN yang sama), lalu akses:
   ```bash
    http://192.168.1.10:2025

4. Anda akan melihat tampilan layar dari komputer pengirim secara langsung di browser.
   Catatan: Pastikan firewall tidak memblokir koneksi ke port 2025.

### Pro Edition
1. **Double-click `berLayar.exe`**
	(cukup klik dua kali)

2. **Atur parameter di GUI**
	Pilihan pada berLayar Pro memiliki pengaturan untuk monitor, FPS, kualitas, kamera, dsb.

3. Klik **Mulai**; alamat **IP:2025** tampil di panel.
	Informasi akan tampil di panel, terdapat juga informasi waktu berjalan.

4. Buka alamat itu di browser perangkat lain.

5. **Berhenti:** klik **Berhenti** atau tutup console.

---

## Akses dari Perangkat Viewer

- Pastikan host & viewer di **jaringan yang sama**.
- Buka browser di perangkat viewer masukkan `http://IP:2025` pada kolom browser (URL).

---

## Tips Kinerja

- **Lite:** cocok untuk perangkat spesifikasi minim.
- **Pro/Exclusive:** kurangi FPS/kualitas/skala bila performa rendah.
- Gunakan LAN/Wi-Fi 5/6 untuk latensi lebih rendah.
- Kamera akan menaikkan beban encode, pastikan komputer dan router anda terjamin.

---

## Keamanan
- Ditujukan untuk **jaringan lokal**.
- Hindari membagikan IP di jaringan publik tanpa proteksi.
- Matikan aplikasi saat tidak digunakan (Menutup GUI/Console).

---

## Kontak

Ingin versi khusus dengan logo dan teks Anda sendiri?

WhatsApp: **+62899-2277-917**  
Email: rheomie@gmail.com

---

## Lisensi

Aplikasi **Lite Edition** tersedia secara gratis untuk penggunaan pribadi dan edukasi.  
Untuk **Pro Edition & Exclusive Build (Platform Edition):** Silakan hubungi kami untuk kebutuhan kustomisasi atau penggunaan komersial.
