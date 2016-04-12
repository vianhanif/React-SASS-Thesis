Beberapa hal yang perlu diketahui

- Yang diubah adalah file dg extensi *.lyx

- Isilah di menu Document -> Setting -> Latex Preamble
  Beberapa variabel yang penting (nama variable sudah cukup menjelaskan)

\newcommand{\Judul}{REPOSITORY MOBILE LABORATORY}
\newcommand{\DosenPembimbing}{Prof. Dr. I Wayan Simri Wicaksana}
\newcommand{\NamaMahasiswa}{Yudha Yogasara}
\newcommand{\NIRM}{92310029}
\newcommand{\Tahun}{2012}
\newcommand{\TempatLahir}{Bogor}
\newcommand{\TglLahir}{16 Agustus 1987}

\newcommand{\TanggalLulus}{29 Maret 2012}
\newcommand{\KataKunci}{Kata kunci disini}
\newcommand{\JumlahHalamanDepan}{xiii}
\newcommand{\JumlahHalaman}{117}
\newcommand{\TahunPustaka}{2006:2011}

\newcommand{\KotaPenulis}{Jakarta}
\newcommand{\TglTulis}{Mei 2012}

\newcommand{\Rektor}{Prof. Dr. E.S. Margianti, SE, MM}
\newcommand{\Koordinator}{Prof. Dr. Yuhara Sukra MSc}
\newcommand{\Direktur}{Prof. Dr. Dharma Tintri, SE.Ak, MBA}
\newcommand{\Kaprodi}{Dr. Yuhilza Hanum SSi, SKom, MEng}


- Logo Gunadarma letakkan di direktori images

- file hypenation koreksi made-hypen.tex harus diletakkan pada direktori yang setingkat. 
File ini bisa saja diubah ditambahi bila menemukan pemenggalan yang tidak tepat.

- Pada bagian Abstraksi hati-hati terutama yang ada code "LaTeX" (ERT berwarna merah). 
Beberapa paragraf pada bagian abstraksi memiliki spasi single.
  Pada bagian yang ada \noindent setelahnya ada spasi 

- Spasi dokumen ini adalah one-and-half (saya memutuskan tidak pakai double, terlalu membuang kertas)


