# postes-pertama
#tugas postes pertama Vincemnz Reynrd Citro
while True:
# saya menggunakan while true agar saat user salah menginput nama nim kelas dan asal sekolah maka akan kembali ke input
    user = input("masukkan username: ")
    nim = input("masukkan nim: ")
    kelas = input("masukan kelas: ")
    asalsekolah = input("masukan asal sekolah: ")
    if user == "vincenz reynard citro" and nim == "2309116080" and kelas == "sistem informasi b" and asalsekolah == "sma sunodia":
        print(user)
        print(nim)
        print(kelas)
        print(asalsekolah)
        print( "anda telah login" )
        break
    else:
        print("nama salah")
        print("nim salah")
        print("kelas salah")
        print("asal sekolah salah")
        #ini adalah data yang harus di isi jika benar maka akan muncul anda telah login dan akan lanjut ke input berat dalam kg dan jika salah maka akan muncul nama salah, nim salah, kelas salah dan asal sekolah salah dan akan kembali ke pengisian biodata
beratkg = float(input("masukan berat dalam kilogram: "))
#saya menggunakan float agar user dapat menginput berat dalam desimal
while True:
#saya menggunakan while true agar saat user menginput selain angka 1,2 dan 3 maka akan kembali ke input
    print("ketik 1 untuk pounds lb")
    print("ketik 2 untuk ounce ons")
    print("ketik 3 untuk gram g")
    pilih = input ()
    #saya menggunakan ketik 1,ketik 2 dan ketik 3 untuk memudahkan user memilih ingin mengubah berat kilogram ke lb, ons dan gram
    if pilih == "1":
        hasillb = beratkg * 2.2046
        print(f"hasilnya dalam lb adalah {hasillb}")
        pass
        #jika user mengetik 1 maka akan muncul hasil dari berat dalam kilogram dikali dengan 2.2046 yang hasilnya berat dalam pounds lb
    elif pilih == "2":
        hasilons = beratkg * 35.274
        print(f"hasilnya dalan ons adalah {hasilons}")
        #juka user mengetik 2 maka akan muncul hasil dari berat dalam kilogram dikali dengan 35.274 yang hasilnya berat dalam ons 
    elif pilih == "3":
        hasilg = beratkg * 1000
        print(f"hasilnya dalam g adalah {hasilg}")
        #jika user mengetik 3 maka akan muncul hasil berat dalam kilogram dikali dengan 1000 yang hasilnya berat dalam gram
        break 
    else:
        print("input salah")

  
[postes pertama.drawio.pdf](https://github.com/vincenzrey/postes-pertama/files/12715953/postes.pertama.drawio.pdf)
![Screenshot 2023-09-25 215838](https://github.com/vincenzrey/postes-pertama/assets/144880422/4a176353-8cf3-4dcb-96f2-fa2b37786e83)

