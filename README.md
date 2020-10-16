# Pengkorvesi-satuan-suhu
#Script sederhana ini dibuat menggunakan bahasa phyton dan kegunaannya adalah untuk dapat mengkonversi ke satuan suhu apapun
print("PENGKONVERSI TEMPERATURE SUHU")

print("1: Hitung dari satuan celcius")
print("2: Hitung dari satuan reamur")
print("3: Hitung dari satuan fahrenheit")
print("4: Hitung dari satuan kelvin")
suhu = float(input("pilih mana yang ingin anda ketahui : "))
if suhu == 1:
         print("   1: celcius ke reamur")
         print("   2: celcius ke fahrenheit")
         print("   3: celcius ke kelvin")
         suhu2 = float(input("Mana yang ingin anda ketahui : "))
         if suhu2 == 1:
            b = float(input("Masukkan suhu dalam celcius : "))
            a = 4/5 * b
            print("Hasilnya adalah =", a, "Reamur")
         elif suhu2 == 2:
            d = float(input("Masukkan suhu dalam celcius: "))
            c = 9/5 * d + 32
            print("Hasilnya adalah =", c, "Fahrenheit")
         elif suhu2 == 3:
            e = float(input("Masukkan suhu dalam celcius : "))
            f = e + 273
            print("Masukkan suhu dalam celcius : ", f, "Kelvin")
elif suhu == 2:
          print("   1: reamur ke celcius")
          print("   2: reamur ke fahrenheit")
          print("   3: reamur ke kelvin")
          suhu3 = float(input("Mana yang ingin anda ketahui : "))
          if suhu3 == 1:
             g = float(input("Masukkan suhu dalam reamur : "))
             h = 5/4 * g
             print("Hasilnya adalah =", h, "Celcius")
          elif suhu3 == 2:
             i = float(input("Masukkan suhu dalam reamur : "))
             j = (9/4 * i) + 32
             print ("Hasilnya adalah =",j,"Fahrenheit")
          elif suhu3 == 3:
             k = float(input("Masukkan suhu dalam reamur : "))
             l = (5/4 * k) + 273
             print ("Hasilnya adalah =",l,"Kelvin" )
elif suhu == 3:
          print("   1: fahrenheit ke celcius")
          print("   2: fahrenheit ke reamur")
          print("   3: fahrenheit ke kelvin")
          suhu4 = float(input("Mana yang ingin anda ketahui : "))
          if suhu4 == 1:
             m = float(input("Masukkan suhu dalam fahrenheit : "))
             n = 5/9 * (m - 32)
             print ("Hasilnya adalah =",n,"Celcius")
          elif suhu4 == 2:
             o = float(input("Masukkan suhu dalam fahrenheit : "))
             p = 4/9 * (o - 32)
             print ("Hasilnya adalah =",p,"Reamur")
          elif suhu4 == 3:
             q = float(input("Masukkan suhu dalam fahrenheit : "))
             r = 5/9 * (q - 32)
             s = r + 273
             print ("Hasilnya adalah =",s,"Kelvin")
elif suhu == 4:
           print("   1: kelvin ke celcius")
           print("   2: kelvin ke reamur")
           print("   3: kelvin ke fahrenheit")
           suhu5 = float(input("Mana yang ingin anda ketahui : "))
           if suhu5 == 1:
             t = float(input("Masukkan suhu dalam kelvin :"))
             u = t - 273
             print ("Hasilnya adalah =",u,"Celcius") 
           elif suhu5 == 2:
             v = float(input("Masukkan suhu dalam kelvin :"))
             w = 4/5 * (v - 273)
             print ("Hasilnya adalah =",w,"Reamur")
           elif suhu5 == 3: 
             x = float(input("Masukkan suhu dalam kelvin : "))
             y = x - 273
             z = 9/5 * y + 32
             print ("Hasilnya adalah =",z,"Fahrenheit")
