Module yang perlu diinstal :
pip install python-docx
pip install pdfplumber
pip install Sastrawi
pip install nltk

Format dokumen yang dapat dijalankan :
.txt
.docx
.pdf

preprocessing tahapan :
1. Ubah dokumen menjadi list kalimat
2. Cleaning atau filtering
3. Case folding
4. Stemming
5. Tokenizing
6. Stopword Removal
7. Hapus item list kosong

Metode yang digunakan dalam meghitung kemiripan kata adalah metode machine learning tradisional : Jaccard Similarity dan Cosine Similarity (tanpa library)

Sistem hanya dapat membandingkan dua dokumen berbahasa Indonesia

Hasil analisis :
Metode cosine similarity memberikan hasil yang lebih baik dibandingkan metode Jaccard similarity. Hal ini dikarenakan dalam peroses perhitungannya, Jaccard similarity mengabaikan kata yang sama sedangkan metode cosine similarity masih mempertimbangkan adanya kata yang sama dalam satu kalimat atau dokumen.