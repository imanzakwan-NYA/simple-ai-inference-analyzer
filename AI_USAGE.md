# Rekod Penggunaan AI Code Assistant

## 1. Nama AI Code Assistant
ChatGPT

## 2. Prompt yang Digunakan
"Bagaimana cara membaca fail CSV menggunakan pandas dan menapis data mengikut nilai confidence threshold 0.70 dalam Python?"

## 3. Cadangan yang Diberikan oleh AI
AI memberikan contoh penggunaan `pd.read_csv()` untuk membaca fail dan kaedah pemfilteran data `df[df['confidence'] >= threshold]`.

## 4. Bahagian Kod yang Dibantu
Fungsi `load_data()` dan `filter_data()` di dalam fail `analysis.py`.

## 5. Perubahan yang Saya Lakukan
Saya menambah semakan pengesahan (validation) untuk memastikan julat threshold berada antara 0.0 hingga 1.0, serta menambah `try-except` untuk menangkap ralat sekiranya fail CSV tidak wujud.

## 6. Cara Saya Menguji Kod
Saya menjalankan `python main.py`, memasukkan nilai input `0.70`, dan menyemak sama ada bilangan rekod yang dipaparkan dalam terminal adalah tepat iaitu 7 rekod.

## 7. Manfaat AI Code Assistant
Mempercepatkan pemahaman sintaks perpustakaan Pandas dan mengurangkan masa penulisan kod dari awal.

## 8. Batasan AI Code Assistant
Kod yang dicadangkan oleh AI kadangkala terlalu umum, jadi saya perlu mengubah suai struktur fungsi supaya sepadan dengan modul dan parameter soalan amali.