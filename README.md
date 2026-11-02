# Mini Project DNA to Protein — Bioinformatika (by OmicsLite)

Mini project Python ini dibuat oleh **OmicsLite** sebagai bahan belajar dasar-dasar **bioinformatika** menggunakan Python. Project ini dirancang untuk pemula yang ingin memahami bagaimana informasi genetik dalam DNA diterjemahkan menjadi protein melalui proses transkripsi dan translasi.

Kamu bisa menjalankannya langsung di Google Colab, atau mengunduh filenya dan menjalankannya di komputer/laptop sendiri. Tidak diperlukan dataset eksternal karena project ini menggunakan sekuens DNA yang sudah disediakan di dalam notebook.

## Tentang Project

Notebook ini berisi 5 latihan singkat seputar proses DNA transcription dan protein translation:

1. **Input DNA Sequence** — memasukkan sekuens DNA sebagai input untuk proses analisis menggunakan Python.
2. **Transcribe DNA → RNA** — mengubah sekuens DNA menjadi mRNA melalui proses transkripsi menggunakan library **Biopython**.
3. **Translate RNA → Protein** — menerjemahkan sekuens mRNA menjadi sekuens protein berdasarkan codon table.
4. **Identify Start and Stop Codons** — mengidentifikasi start codon (AUG) dan stop codons (UAA, UAG, UGA) pada sekuens mRNA.
5. **Visualize the Central Dogma** — membuat visualisasi sederhana proses Central Dogma of Molecular Biology, mulai dari DNA, mRNA, hingga protein menggunakan **Matplotlib**.

Library utama yang dipakai: **Biopython** dan **Matplotlib**.

---

## 🚀 Cara 1: Jalankan Langsung di Google Colab (Direkomendasikan)

Ini cara paling mudah karena kamu tidak perlu install apa pun di komputer.

1. Buka link Colab project ini: 👉 [Buka di Google Colab]((https://colab.research.google.com/drive/10jl2c7FmzQu2R7gPpjU0fAgDeamVGs59?usp=sharing))
2. **Login** dulu ke akun Google kamu (kalau belum login).
3. **PENTING — jangan edit file aslinya langsung.** Simpan salinan ke Drive kamu sendiri dengan cara:
   - Klik menu **File** di pojok kiri atas
   - Pilih **Save a copy in Drive** (Simpan salinan di Drive)
   - Colab akan otomatis membuka tab baru berisi salinan file tersebut di Drive kamu (biasanya diberi nama "Copy of ...")
4. Kerjakan, edit, dan jalankan project di **file salinan** tersebut, bukan di file original.
5. Untuk menjalankan kode, klik ikon ▶️ (play) di sebelah kiri setiap cell, atau pilih **Runtime > Run all** untuk menjalankan semua cell sekaligus.

---

## 💻 Cara 2: Download File dan Jalankan di Komputer/Laptop

Kalau kamu ingin mengerjakan project secara offline di komputer sendiri, ikuti langkah berikut.

### A. Download File dari Colab

1. Buka link Colab di atas.
2. Klik menu **File > Download**, lalu pilih salah satu:
   - **Download .ipynb** → untuk file Jupyter Notebook (dengan cell-cell kode + penjelasan)
   - **Download .py** → untuk file Python biasa (script murni, tanpa format notebook)
3. File akan otomatis tersimpan di folder **Downloads** komputer kamu.

### B. Aplikasi untuk Membuka File di Laptop

| Tipe File | Aplikasi yang Bisa Dipakai |
|---|---|
| `.ipynb` | **Jupyter Notebook** / **JupyterLab**, **VS Code** (dengan extension Python + Jupyter), **Anaconda Navigator**, atau PyCharm Professional |
| `.py` | **VS Code**, **PyCharm**, **Sublime Text**, **Notepad++**, atau text editor apa pun (untuk sekadar membaca kodenya) |

### C. Cara Menjalankan File `.ipynb` di Laptop

**Opsi paling mudah — pakai VS Code:**

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install Python dari [python.org](https://www.python.org/downloads/) (centang "Add to PATH" saat install)
3. Buka VS Code, pasang extension **Python** dan **Jupyter** (cari di tab Extensions)
4. Buka file `.ipynb` yang sudah kamu download (**File > Open File**)
5. Pilih Python interpreter/kernel di pojok kanan atas, lalu jalankan tiap cell dengan tombol ▶️

**Opsi lain — pakai Jupyter Notebook langsung:**

1. Install Python dari [python.org](https://www.python.org/downloads/)
2. Buka Terminal/Command Prompt, lalu install Jupyter:

   ```bash
   pip install notebook
   ```

3. Jalankan Jupyter dengan mengetik:

   ```bash
   jupyter notebook
   ```

4. Browser akan otomatis terbuka. Arahkan ke folder tempat file `.ipynb` disimpan, lalu klik file tersebut untuk membukanya.

**Opsi lain — pakai Anaconda (paling lengkap untuk pemula data science):**

1. Download & install [Anaconda](https://www.anaconda.com/download)
2. Buka **Anaconda Navigator**, lalu klik **Launch** pada Jupyter Notebook atau JupyterLab
3. Arahkan ke folder file `.ipynb` kamu dan buka

### D. Cara Menjalankan File `.py` di Laptop

1. Pastikan Python sudah terinstall (cek dengan mengetik `python --version` di terminal)
2. Install library yang dibutuhkan project ini:

   ```bash
   pip install biopython matplotlib
   ```

3. Jalankan file dengan perintah:

   ```bash
   python nama_file.py
   ```

---

## 📦 Requirements

Kalau menjalankan di Google Colab, install library melalui cell berikut:

```python
!pip install biopython matplotlib
```

Kalau menjalankan di laptop sendiri, install terlebih dahulu:

```bash
pip install biopython matplotlib
```

Library yang digunakan:

- **Biopython** — untuk proses transkripsi DNA menjadi mRNA dan translasi mRNA menjadi protein.
- **Matplotlib** — untuk membuat visualisasi Central Dogma of Molecular Biology.

---

## 🎯 Learning Outcomes

Setelah menyelesaikan mini project ini, kamu diharapkan mampu:

- Memahami konsep dasar Central Dogma of Molecular Biology.
- Melakukan transkripsi DNA menjadi mRNA menggunakan Python.
- Melakukan translasi mRNA menjadi sekuens protein menggunakan codon table.
- Mengidentifikasi start codon dan stop codon.
- Membuat visualisasi sederhana proses DNA transcription dan protein translation.

---

## 📚 References

- [Biopython Documentation](https://biopython.org/)
- [NCBI Genetic Codes](https://www.ncbi.nlm.nih.gov/Taxonomy/Utils/wprintgc.cgi)

---

**Happy Coding & Exploring Bioinformatics! 🧬**

*OmicsLite — Bioinformatics Research Starter Program*
