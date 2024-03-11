## Daftar Pertanyaan untuk berkonsultasi ke dosen pembimbing
- [ ] apakah tidak masalah dalam proses pemilihan data tweets hanya diambil tweets yang memiliki mentions?
  - karena dari **jumlah data: 20895** jika setelah diambil hanya tweets yang memiliki mentions **tersisa: 5428**.
  - alasannya supaya nantinya ketika pembuatan atau visualisasi graph menjadi lebih ringan, karena hanya mengambil konten - konten yang sifatnya 2 arah.

- [ ] untuk pembuatan **topic modelling** masih dilakukan eksplorasi dikarenakan banyaknya **slang** yang tersebar sehingga sulit untuk dikenali oleh **library NLP** sehingga banyak normalisasi teks yang tidak dapat dilakukan.
- [ ] rencana nantinya topic modelling hanya akan diterapkan pada **10 nodes teratas** berdasarkan nilai sentralitas. 
  - alasannya untuk mempersingkat waktu karena hanya menganalisa aktor - aktor yang memiliki peran penting diambil berdasarkan nilai sentralitasnya.