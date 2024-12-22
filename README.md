# **Tubes2_AI**

## Deskripsi Tugas
Tugas Besar 2 ini merupakan pembelajaran machine learning menggunakan KNN dengan 3 metric: euclidean, manhattan, dan minkowski serta Naive Bayes untuk memprediksi legitimasi sebuah URL

## **Anggota Kelompok 08** 

- Daffari Adiyatma (18222003)
- Aththariq Lisan Q. D. S. (18222013)
- Muhammad Rafly (18222067)
- Alvin Fadhilah Akmal (18222079)

## **Cara Menjalankan Proyek**

### **Langkah-Langkah**

1. Clone repository:

   ```bash
   git clone https://github.com/aththariq/Tubes2_AI.git
   cd Tubes2_AI
   ```

2. Buat virtual environment:

   ```bash
   # Linux/Mac
   python3 -m venv venv
   source venv/bin/activate

   # Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. Instal dependency:

   ```bash
   pip install -r requirements.txt
   ```

4. Instal Jupyter Notebook (jika belum terinstal):

   ```bash
   pip install notebook
   ```

5. Jalankan Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Pilih kernel **Python (venv)** di Jupyter Notebook. Jika kernel belum tersedia, tambahkan virtual environment sebagai kernel:

   ```bash
   python -m ipykernel install --user --name=venv --display-name "Python (venv)"
   ```

7. Jika Anda mengunduh library baru, jangan lupa memperbarui `requirements.txt` agar library tersebut dapat digunakan oleh tim:

   ```bash
   pip freeze > requirements.txt
   ```

8. Setiap kali bekerja dengan proyek ini, pastikan virtual environment aktif:

   ```bash
   # Linux/Mac
   source venv/bin/activate

   # Windows
   venv\Scripts\activate
   ```
