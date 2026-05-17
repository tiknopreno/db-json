# Mock API JSON Server

Mock API ini dibuat menggunakan `json-server` dan dapat digunakan untuk kebutuhan frontend development, testing API, maupun simulasi backend.

## Base URL

```bash
https://my-json-server.typicode.com/tiknopreno/db-json
````

---

# Daftar Endpoint

| Endpoint         | Deskripsi                |
| ---------------- | ------------------------ |
| `/dataPengguna`  | Data pengguna            |
| `/dataProgress`  | Data progress pengguna   |
| `/dataBahanAjar` | Data bahan ajar          |
| `/dataTracking`  | Data tracking pengiriman |
| `/dataTransaksi` | Data transaksi           |

---

# GET Data Pengguna

## GET Semua Data Pengguna

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna
```

---

## GET Pengguna Berdasarkan ID

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna/1
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna/1
```

---

## GET Pengguna Berdasarkan Role

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna?role=Administrator
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna?role=Administrator"
```

---

## GET Pengguna Berdasarkan Lokasi

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna?lokasi=Pusat
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna?lokasi=Pusat"
```

---

# GET Data Progress

## GET Semua Data Progress

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress
```

---

## GET Progress Berdasarkan ID

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress/1
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress/1
```

---

## GET Progress Berdasarkan ID User

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress?iduser=1
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress?iduser=1"
```

---

## GET Progress Berdasarkan Kode Barang

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress?kodeBarang=MSIM440201
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataProgress?kodeBarang=MSIM440201"
```

---

# GET Data Bahan Ajar

## GET Semua Data Bahan Ajar

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar
```

---

## GET Bahan Ajar Berdasarkan ID

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar/1
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar/1
```

---

## GET Berdasarkan Kode Barang

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?kodeBarang=MSIM440201
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?kodeBarang=MSIM440201"
```

---

## GET Berdasarkan Jenis Barang

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?jenisBarang=BMP
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?jenisBarang=BMP"
```

---

## GET Berdasarkan Edisi

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?edisi=4
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?edisi=4"
```

---

# Pagination

## GET Pagination

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?_page=1&_limit=5
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?_page=1&_limit=5"
```

---

# Sorting

## Sorting Harga Ascending

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?_sort=harga&_order=asc
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?_sort=harga&_order=asc"
```

---

## Sorting Harga Descending

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?_sort=harga&_order=desc
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?_sort=harga&_order=desc"
```

---

# GET Data Tracking

## GET Semua Data Tracking

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking
```

---

## GET Tracking Berdasarkan ID

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking/2023001234
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking/2023001234
```

---

## GET Tracking Berdasarkan Status

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking?status=Dikirim
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking?status=Dikirim"
```

---

## GET Tracking Berdasarkan Ekspedisi

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking?ekspedisi=JNE
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataTracking?ekspedisi=JNE"
```

---

# GET Data Transaksi

## GET Semua Data Transaksi

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi
```

---

## GET Transaksi Berdasarkan ID

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi/TX-202605001
```

### cURL

```bash
curl https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi/TX-202605001
```

---

## GET Transaksi Berdasarkan ID User

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi?idUser=1
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi?idUser=1"
```

---

## GET Transaksi Berdasarkan ID Bahan Ajar

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi?idBahanAjar=2
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataTransaksi?idBahanAjar=2"
```

---

# Search Data

## Search Nama Barang

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?namaBarang_like=sistem
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataBahanAjar?namaBarang_like=sistem"
```

---

## Search Nama Pengguna

```bash
GET https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna?nama_like=Rina
```

### cURL

```bash
curl "https://my-json-server.typicode.com/tiknopreno/db-json/dataPengguna?nama_like=Rina"
```

---

# Teknologi

* JSON Server
* My JSON Server
* REST API

---

# Catatan

Dokumentasi ini hanya semeta-mata ingin membantu teman-teman agar lebih memahami gambaran simulasi rest full api.

* Endpoint ini digunakan untuk mock API/testing.
* Data bersifat statis.
* Sangat cocok untuk simulasi frontend web maupun mobile.
* Mendukung filtering, sorting, pagination, dan search sederhana.


```

