# 🗺️ GeoJSON Jalan Kelurahan Cijagra

## 📘 Deskripsi
Data ini berisi representasi digital beberapa ruas jalan di wilayah tersebut, disajikan dalam format **FeatureCollection** dengan tipe geometri **LineString**.

---

## 📍 Lokasi Data
- **Wilayah:** Kelurahan Cijagra 
- **Kecamatan:** Lengkong
- **Kota:** Bandung  
- **Provinsi:** Jawa Barat, Indonesia  

---

## 🧩 Struktur GeoJSON
File `jalan_kelurahan_cijagra.geojson` terdiri dari 6 fitur (jalan):

| No | Nama Jalan         | Tipe Geometri | Jumlah Titik Koordinat |
|----|--------------------|----------------|-------------------------|
| 1  | Jalan Nilem Raya   | LineString     | 4                       |
| 2  | Jalan Nilem 1      | LineString     | 5                       |
| 3  | Jalan Nilem 2      | LineString     | 2                       |
| 4  | Jalan Nilem 3      | LineString     | 4                       |
| 5  | Jalan Beunteur     | LineString     | 4                       |
| 6  | Jalan Boncenang    | LineString     | 3                       |

---

## 🧭 Format Data
Berikut contoh salah satu fitur dari GeoJSON:

```json
{
  "type": "Feature",
  "properties": {
    "name": "Jalan Nilem Raya"
  },
  "geometry": {
    "type": "LineString",
    "coordinates": [
      [107.62083486708923, -6.935094983889698],
      [107.62023156346277, -6.935656773795216],
      [107.61990588628413, -6.936229162822428],
      [107.61969232747884, -6.93676445193033]
    ]
  }
}
```
## 🗺️ Visualisasi Hasil GeoJSON
<img width="1003" height="924" alt="image" src="https://github.com/user-attachments/assets/d874b77b-0b71-4411-8ea6-f89a2fd68cfa" />

Garis **Abu** menunjukkan jalur jalan yang telah dibuat menggunakan tipe `LineString`.





