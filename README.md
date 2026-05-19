   #!/bin/bash
   # This script calculates simple interest given principal,
   # annual rate of interest and time period in years.

   # Do not use this in production. Sample purpose only.

   # Author: Upkar Lidder (IBM)
   # Additional Authors:
   # <your GitHub username>

   # Input:
   # p, principal amount
   # t, time period in years
   # r, annual rate of interest

   # Output:
   # simple interest = p*t*r

   echo "Enter the principal:"
   read p
   echo "Enter time period in years:"
   read t
   echo "Enter rate of interest per year:"
   read r

   s=$(echo "scale=2; $p * $t * $r / 100" | bc)
   echo "The simple interest is: "
   echo $s

   #!/bin/bash
   # Skrip ini menghitung bunga sederhana berdasarkan pokok,
   # suku bunga tahunan, dan periode waktu dalam tahun.

   # Jangan gunakan ini di produksi. Hanya untuk tujuan contoh.

   # Penulis: Upkar Lidder (IBM)
   # Penulis Tambahan:
   # <nama pengguna GitHub Anda>

   # Input:
   # p, jumlah pokok
   # t, periode waktu dalam tahun
   # r, suku bunga tahunan

   # Output:
   # bunga sederhana = p*t*r

   echo "Masukkan pokok:"
   read p
   echo "Masukkan periode waktu dalam tahun:"
   read t
   echo "Masukkan suku bunga per tahun:"
   read r

   s=$(echo "scale=2; $p * $t * $r / 100" | bc)
   echo "Bunga sederhana adalah: "
   echo $s
