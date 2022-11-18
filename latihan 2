Created on Fri Nov 18 14:19:48 2022

@author: Hawa Aprilia Utami
"""

# penjumlahan dengan fungsi rekursif
def penjumlahan(x,y):
    if x == 0:
        return y
    else:
        return 1 + penjumlahan(x-1,y)

angka1 = int(input("Masukkan angka pertama: "))
angka2 = int(input("Masukkan angka kedua: "))
print(penjumlahan(angka1,angka2))

# desimal ke biner
def desimal_ke_biner(x):
    if x == 0:
        return 0
    else:
        return x % 2 + 10 * desimal_ke_biner(int(x/2))

print(desimal_ke_biner(int(input('masukkan angka desimal: '))))
