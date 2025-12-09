# Praktikum Grafika Komputer

Repositori ini berisi materi dan kode untuk Praktikum Mata Kuliah Grafika Komputer. Setiap modul berisi notebook (`.ipynb`) dan/atau skrip Python yang mendemonstrasikan konsep grafika komputer sesuai pertemuan.

## Struktur Folder

- `Modul_1/`
  - `praktikum1.py`, `praktikum2.py`, `praktikum3.py`, `posttest.ipynb`, `praktikum4.ipynb`, `tugas.ipynb`
- `Modul_2/`
  - `Praktikum21.ipynb`
- `Modul_3/`
  - `Praktikum31.ipynb`
- `Modul_4/`
  - `Praktikum4.ipynb`
- `modul_5/`
  - `Praktikum5.ipynb`, `Tugas.ipynb`
- `Modul_6/`
  - `Praktikum6.ipynb`, `Tugas.ipynb`
- `Modul_7/`
  - `Praktikum7.ipynb`, `tugas.ipynb`
- `Teori/`
  - `TugasDDAdanBressenhem.ipynb`

Catatan: Penamaan folder mengikuti yang ada di kelas; beberapa modul menggunakan huruf kapital yang berbeda-beda sesuai sumber asli.

## Prasyarat

- Python 3.13 (disarankan menggunakan launcher `py` di Windows)
- VS Code + ekstensi Python (opsional Jupyter)
- Paket Python umum (tergantung materi per modul):
  - `numpy`, `matplotlib`
  - Tambahan lain sesuai kebutuhan modul (misalnya `opencv-python`, dll.)

Instalasi paket (Windows PowerShell):

```
py -m pip install --upgrade pip
py -m pip install numpy matplotlib
```

## Menjalankan Notebook

Pilihan 1 — di VS Code:

- Buka file `.ipynb` (mis. `modul_5/Praktikum5.ipynb`)
- Pilih kernel/interpreter Python 3.x yang benar (Command Palette → "Python: Select Interpreter")
- Jalankan sel satu per satu

Pilihan 2 — via Jupyter Lab/Notebook:

```
py -m pip install jupyterlab
py -m jupyter lab
```

Lalu buka notebook dari browser.

## Menjalankan Skrip Python

Contoh di `Modul_1`:

```
py Modul_1\praktikum1.py
py Modul_1\praktikum2.py
```

Gunakan `py` (bukan `python`) jika Windows App Execution Aliases untuk `python.exe` masih aktif.

## Rekomendasi Virtual Environment (opsional)

```
py -3.13 -m venv .venv
.\.venv\Scripts\activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt  # jika tersedia
```

Setelah aktif, pilih interpreter `.venv` di VS Code.

## Tips & Troubleshooting (Windows)

- Jika perintah `python` memunculkan pesan "Python was not found", gunakan `py` atau nonaktifkan App Execution Aliases (Settings → Apps → Advanced app settings → App execution aliases → OFF untuk `python.exe`/`python3.exe`).
- Di VS Code, pastikan interpreter benar: Command Palette → "Python: Select Interpreter".

## Kontribusi

Repositori ini ditujukan untuk pembelajaran di kelas. Silakan buat branch atau pull request jika ingin menambahkan perbaikan/peningkatan materi.

## Lisensi

Tidak ada lisensi khusus yang disertakan. Gunakan untuk keperluan akademik/praktikum.
