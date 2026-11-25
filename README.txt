SISTEM CARIAN SLIP PENCAPAIAN MURID V2 — SEKOLAH EDUCREATOR

KANDUNGAN PAKEJ
index.html  - laman carian (muat naik ke GitHub Pages)
Code.gs     - kod Google Apps Script untuk folder PDF
README.txt  - panduan pemasangan ini

KONFIGURASI
Nama sekolah : SEKOLAH EDUCREATOR
ID folder Drive: 1oeO_KsUbgbFtCD6BZKRDIJH_4d1Aj7nG
Apps Script    : https://script.google.com/macros/s/AKfycbzHzr09_GtDext3U9drR5WzzEdIqe3cOWdP9ndnOSeDElD5bq5GIb6HYLAeRj6TaMdl/exec
Logo sekolah   : https://iili.io/ofvYYml.md.png

FORMAT NAMA FAIL
NoKP_JENISPENTAKSIRAN_TAHUN.pdf
Contoh:
120101011234_UASA_2026.pdf
120101011234_UPSA_2026.pdf
120101011234_PBD_AKHIR_2026.pdf

SISTEM MENYOKONG:
- Carian semua PDF yang dimulakan dengan NoKP yang padan tepat
- Pelbagai jenis pentaksiran dan tahun untuk NoKP yang sama
- Pratonton PDF dan muat turun PDF melalui Apps Script
- Header gradient, hover effect, mesra telefon pintar

PANDUAN GOOGLE APPS SCRIPT
1. Log masuk akaun Google yang mempunyai akses kepada folder Drive tersebut.
2. Buka projek Apps Script yang mempunyai URL Web App di atas.
3. Gantikan kandungan Code.gs dengan kod dalam pakej ini; tekan Save.
4. Jalankan fungsi ujiSambungan sekali dan luluskan kebenaran Drive.
5. Deploy > Manage deployments > Edit (ikon pensel) > New version > Deploy.
6. Semak deployment Web App: Execute as Me. Akses 'Anyone' hanya jika
   dibenarkan oleh pihak sekolah dan kawalan akses tambahan telah dipasang.

PANDUAN GITHUB PAGES
1. Cipta repository GitHub baharu atau buka repository sedia ada.
2. Muat naik index.html ke root repository.
3. Settings > Pages > Deploy from a branch > main > /(root) > Save.
4. Uji dengan NoKP rekaan dan fail PDF contoh dalam folder Drive.

PENTING
- Logo EDUCREATOR dimuat melalui pautan HTTPS, jadi perlu internet.
- Fail PDF perlu berada terus dalam folder Drive yang ditetapkan.
- Sistem tidak memerlukan PDF dikongsi sebagai 'Anyone with the link'.
- Versi asas menggunakan NoKP sahaja dan BUKAN pengesahan identiti.
  Dapatkan kelulusan serta tambah PIN/akses individu sebelum digunakan
  dengan data sebenar murid. Jangan terbitkan akses awam bagi data peribadi
  tanpa kawalan yang sepadan.
- Had fail PDF semasa: 8 MB setiap satu.
- Fungsi sebenar bergantung pada kebenaran dan deployment Apps Script.
  Sambungan Drive tidak dapat diuji dari persekitaran pembinaan fail.
