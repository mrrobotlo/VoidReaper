 # VoidReaper

VoidReaper adalah tool pengujian stres HTTP berbasis Node.js yang dirancang untuk mensimulasikan traffic tinggi ke sebuah endpoint. Alat ini dapat digunakan secara sah untuk pengujian performa server, firewall, dan mekanisme mitigasi DDoS.

> ⚠️ **Peringatan:**
> VoidReaper hanya boleh digunakan untuk tujuan pembelajaran atau pengujian sistem yang Anda miliki atau telah mendapat izin eksplisit. Penyalahgunaan alat ini untuk menyerang sistem tanpa izin adalah ilegal dan dapat dikenai sanksi hukum.

## Fitur

- Mendukung HTTP dan HTTPS
- Kustomisasi jumlah thread (permintaan simultan)
- Permintaan GET cepat dan terus-menerus
- Dapat digunakan untuk benchmark dasar

## Persyaratan

- Node.js (v14 atau lebih baru)

## Instalasi


git clone https://github.com/mrrobotlo/VoidReaper.git
cd VoidReaper

Cara Menjalankan

node VoidReaper.js <target_url> [threads]

<target_url> : URL lengkap target yang akan diuji, termasuk protokol (http:// atau https://)

[threads] (opsional) : Jumlah thread atau permintaan paralel yang akan dikirim (default: 50)


Contoh:

node VoidReaper.js http://localhost 100

Perintah di atas akan menjalankan 100 permintaan paralel ke http://localhost.

Catatan Tambahan

Gunakan alat ini secara bertanggung jawab.

Untuk pengujian pada sistem produksi, selalu lakukan koordinasi dengan administrator jaringan terkait.

Tools ini bukan pengganti untuk tools benchmark profesional seperti Apache Benchmark (ab) atau JMeter, namun berguna untuk simulasi ringan dan pembelajaran dasar.



---

Developer: mrrobotlo
