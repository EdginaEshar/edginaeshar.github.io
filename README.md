# Edgina Eshar - GitHub Pages Legal Portal

Panduan upload dan aktivasi GitHub Pages untuk domain:
`https://edginaeshar.github.io/`

---

### 📂 Struktur File yang Dibuat

Folder ini (`github_pages/`) sudah siap 100% untuk di-upload langsung ke repositori GitHub:

1. **`privacy-policy.html`** ➔ URL: `https://edginaeshar.github.io/privacy-policy.html`
   - Sesuai dengan URL yang Anda minta dan yang sudah dipasang di dalam aplikasi.
   - Bersifat general untuk seluruh aplikasi & game di akun developer Edgina Eshar.
   - Lengkap dengan standar kebijakan Google Play (AdMob, Firebase Analytics, Crashlytics, Realtime DB, COPPA / perlindungan anak, dan hak hapus data).
2. **`index.html`** ➔ URL: `https://edginaeshar.github.io/`
   - Halaman portal utama (*Legal & Transparency Center*) yang menghubungkan ketiga dokumen hukum dengan desain modern.
3. **`terms.html`** ➔ URL: `https://edginaeshar.github.io/terms.html`
   - Ketentuan layanan (*Terms of Service*) dan lisensi penggunaan aplikasi.
4. **`disclaimer.html`** ➔ URL: `https://edginaeshar.github.io/disclaimer.html`
   - Penegasan status aplikasi independen/fan-made, penafian afiliasi, atribusi hak cipta, serta format pengajuan penghapusan konten (*DMCA / Takedown Request*).

---

### 🚀 Cara Upload ke GitHub (Hanya 2 Menit)

#### Cara 1: Lewat Web GitHub (Paling Mudah & Cepat)
1. Buka browser dan login ke akun GitHub Anda: **`edginaeshar`**.
2. Buat repositori baru bernama: **`edginaeshar.github.io`** (harus bertipe **Public**).
   *(Jika repositori ini sudah ada sebelumnya, langsung buka repositori tersebut).*
3. Klik tombol **"Add file"** ➔ **"Upload files"**.
4. Drag & drop (seret) ke-4 file berikut dari folder `github_pages/`:
   - `index.html`
   - `privacy-policy.html`
   - `terms.html`
   - `disclaimer.html`
5. Beri commit message (misal: `"Initial commit legal portal"`) lalu klik **"Commit changes"**.
6. Masuk ke menu **Settings** repositori ➔ klik tab **Pages** di sebelah kiri.
7. Pastikan pada bagian **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** (atau **master**) / folder: **/(root)**
   - Klik **Save**.
8. Tunggu 1–3 menit, website Anda akan langsung aktif di:
   - `https://edginaeshar.github.io/`
   - `https://edginaeshar.github.io/privacy-policy.html`

---

#### Cara 2: Lewat Git Terminal
Jika Anda terbiasa dengan Git CLI:
```bash
cd "github_pages"
git init
git remote add origin https://github.com/edginaeshar/edginaeshar.github.io.git
git branch -M main
git add index.html privacy-policy.html terms.html disclaimer.html
git commit -m "feat: publish Edgina Eshar legal and privacy portal"
git push -u origin main
```
