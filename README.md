# Putusan Pengadilan Kasus Narkotika dan Psikotropika

## Deskripsi 
Bertujuan untuk menganalisis data terkait kasus-kasus pidana narkotika berdasarkan dokumen keputusan pengadilan yang tersedia. Data diperoleh dari website Mahkamah Agung https://putusan3.mahkamahagung.go.id/ dimana data yang diambil yaitu direktori Pidana Khusus dengan klasifikasi Narkotika dan Psikotropika di Pengadilan Negeri Palembang pada tahun 2023. Putusan yang diambil sebanyak 50 dokumen putusan berupa file PDF. 

## Struktur File
Repositori ini mencakup beberapa file utama : 
1. Narkotika.zip: File arsip yang berisi data mentah yang berhubungan dengan narkotika. Setelah diekstrak, file atau folder di dalamnya akan berisi berbagai informasi yang mencakup dokumen putusan pengadilan.
2. Overview.xlsx: File Excel ini berisi ringkasan data yang lebih komprehensif, berfungsi sebagai pengantar untuk memahami informasi utama terkait narkotika. File ini merupakan summary dari 50 putusan dengan struktur kolom sebagai berikut: 

    | No | No Putusan | Lembaga Peradilan | Barang Bukti | Amar Putusan |
    | ------ | ------ |------------------ | ------------ |------------- |

## Cara Penggunaan
Berikut adalah langkah untuk menggunakan data dari file Overview.xlsx:

'''
url = "https://github.com/Lusy230/Dataset-Narkotika_199_230/raw/main/Overview.xlsx"
response = requests.get(url)
data = pd.read_excel(BytesIO(response.content))
'''

atau bisa menggunakan

'''
git clone https://github.com/Lusy230/Dataset-Narkotika_199_230.git
'''

'''
cd Dataset-Narkotika_199_230
'''

'''
ls
'''



## Credit

Wulan Puspita Rahayu - 20211070311199
Lusy Rohmadhoni - 202110370311230
