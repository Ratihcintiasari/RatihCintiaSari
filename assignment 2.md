#soal pertama 

#pertanyaan : 

#Buatlah 3 rumus fisika dasar dan operasikan rumus tersebut berdasarkan input yang kalian tentukan sendiri

#rumus energi kinetik

a=float(input('masukan massa:'))

   t=float(input('masukan volume:'))

   b=0.5*a*t**2

   print('Ek=', b)



#rumus gaya gravitasi

a=float(input('masukan m1:'))

   t=float(input('masukan m2:'))

   g=float(input('masukan R:'))

   b=6,7*10^2*a*t*g**2

   print('F=', b)




#rumus jarak yang ditempuh (m)

a=float(input('masukan v0:'))

   t=float(input('masukan t:'))

   g=float(input('masukan a:'))

   b=a*t*1/2*g*t**2

   print('S=', b)





#soal kedua 

#pertanyaan : Cobalah buat perumpamaan (if-else) dengan permasalahan sederhana.


a=(input('nilai: '))

  if a == 'AB':

   print ('DI Yogyakarta')

 elif a == 'D':

   print ('Bandung')

 elif a == 'B':

   print ('DKI Jakarta')

 elif a == 'A':

   print ('Banten')

 elif a == 'E':

   print ('Cirebon, Indramayu, Majalengka dan Kuningan')

 elif a == 'E':

   print ('Bogor')

 elif a == 'T':

   print ('Purwakarta, Karawang, Subang')

 elif a == 'Z':

   print ('Garut, Tasikmalaya, Sumedang, Ciamis, dan Banjar')

 elif a == 'H':

   print ('Semarang dengan Salatiga, Kendal, dan Demak')

 elif a == 'L':

   print ('Surabaya')

 elif a == 'W':

   print ('Sidoarjo dan Gresik')

else:

   print('not found')





#soal ketiga

#pertanyaan : Buatlah list sederhana berisikan minimal data diri 20 orang random yang berisi [Nama, Umur, TB, BB]. Kemudian lakukan operasi if-else sederhana untuk memfilter data dari list orang-orang yang anda buat.

data_orang = [

    {"Nama": "Wadi", "Umur": 25, "TB": 170, "BB": 65},

    {"Nama": "Budi", "Umur": 30, "TB": 175, "BB": 70},

    {"Nama": "Diana", "Umur": 13, "TB": 119, "BB": 20},

    {"Nama": "beben", "Umur": 25, "TB": 140, "BB": 15},

    {"Nama": "sumardi", "Umur": 16, "TB": 158, "BB": 45},

    {"Nama": "narisa", "Umur": 23, "TB": 167, "BB": 55},

    {"Nama": "kina", "Umur": 14, "TB": 149, "BB": 23},

    {"Nama": "Winda", "Umur": 16, "TB": 153, "BB": 30},

    {"Nama": "Loli", "Umur": 16, "TB": 152, "BB": 31},

    {"Nama": "Nila", "Umur": 16, "TB": 150, "BB": 35},

    {"Nama": "Putra", "Umur": 18, "TB": 160, "BB": 49},

    {"Nama": "Jajan", "Umur": 38, "TB": 170, "BB": 60},

    {"Nama": "Ojan", "Umur": 28, "TB": 180, "BB": 70},

    {"Nama": "Ratih", "Umur": 19, "TB": 160, "BB": 58},

    {"Nama": "Jingga", "Umur": 15, "TB": 163, "BB": 47},

    {"Nama": "Mara", "Umur": 19, "TB": 160, "BB": 42},

    {"Nama": "Lovi", "Umur": 12, "TB": 130, "BB": 25},

    {"Nama": "Qinta", "Umur": 23, "TB": 170, "BB": 58},

    {"Nama": "Panji", "Umur": 24, "TB": 179, "BB": 60},

    {"Nama": "Fauzan", "Umur": 20, "TB": 172, "BB": 56}]

orang_remaja = []

orang_diantara_22_dan_30 = []
    
for orang in data_orang:

    if orang["Umur"] <=20:

        orang_remaja.append(orang)

for orang in orang_remaja:

    print("Orang yang berumur dibawah 20 tahun:")

    print(f"Nama: {orang['Nama']}") 

    print(f"Umur: {orang['Umur']}") 

    print(f"TB: {orang['TB']} cm") 

    print(f"BB: {orang['BB']} kg")
    
for orang in data_orang:

    if orang["Umur"] >= 22 <= 30:

        orang_diantara_22_dan_30.append(orang)

for orang in orang_diantara_22_dan_30:

    print("Orang yang berumur diantara 22 sampai 30 tahun:")

    print(f"Nama: {orang['Nama']}") 

    print(f"Umur: {orang['Umur']}") 

    print(f"TB: {orang['TB']} cm") 

    print(f"BB: {orang['BB']} kg")


#screenshoot bukti berhasil kode di run

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000119.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000238.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000257.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000410.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000435.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000544.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000610.png)

![Gambar](https://github.com/Ratihcintiasari/dokumentasi/blob/b5e5b916859bfb989541690cd47c7d44d884dc13/Screenshot%202023-09-15%20000625.png)

