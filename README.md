# 🚇 GTFS Static – MRT Jakarta

> Data GTFS Static tidak resmi untuk jaringan **MRT Jakarta**, tersedia untuk umum dan terbuka untuk digunakan.

##  Tentang

Repositori ini menyediakan data **General Transit Feed Specification (GTFS) Static** untuk sistem **Mass Rapid Transit (MRT) Jakarta**. Data ini mencakup informasi rute, jadwal, halte, dan atribut pelayanan lainnya yang mengikuti standar resmi [GTFS](https://gtfs.org/documentation/schedule/reference/).
GTFS Static merupakan format standar industri yang digunakan secara luas di seluruh dunia.

---

## Keabsahan Data

| Keterangan | Detail |
|---|---|
| Data valid per tanggal | **1 Januari 2026** |
| Pembaruan terakhir | 1 Maret 2026 |

> ⚠️ Pastikan selalu menggunakan versi terbaru dari repositori ini untuk akurasi data yang optimal.
---

## Isi Data

Feed GTFS didistribusikan dalam format **file `.zip`** standar yang dapat langsung digunakan dengan berbagai alat dan pustaka GTFS yang tersedia.

File zip berisi berkas-berkas teks (`.txt`) yang mencakup:

| File | Deskripsi |
|---|---|
| `agency.txt` | Informasi operator/perusahaan |
| `calendar.txt` | Jadwal operasional |
| `routes.txt` | Daftar rute layanan |
| `trips.txt` | Perjalanan per rute |
| `stops.txt` | Lokasi dan nama halte |
| `stop_times.txt` | Jadwal kedatangan & keberangkatan |
| `shapes.txt` | Data geometri rute |


## Validasi
Data GTFS ini telah divalidasi menggunakan **MobilityData GTFS Validator**.

🔗 **[Link](https://gtfs-validator-results.mobilitydata.org/04cd0b32-efb2-4cd8-b3f5-c17aa66e48bf/report.html)**


## Lisensi
Data GTFS ini disediakan untuk penggunaan publik. CC0?!?

## Pengembangan
Bisa kali di jadiin .R tapi gwej ga paham.

