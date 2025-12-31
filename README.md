# emvat
emvat bir tane programlama dilidir ve türkçedir
# hangi kodlar var?
EMVAT PROGRAMLAMA DİLİ
=====================

---------------------
1) YAZDIRMA
---------------------
yaz "Merhaba"
yaz 5
yaz 2+2
yaz x
yaz x*3+2

---------------------
2) DEĞİŞKEN TANIMLAMA
---------------------
ata x = 5
ata y = 10
ata z = x+y
ata sonuc = (x+3)*2

---------------------
3) MATEMATİK İFADELERİ
---------------------
2+2
3*3
10/2
5-1
(2+3)*4
x+5
x*y+3

KULLANILABİLEN OPERATÖRLER:
+   -   *   /   ( )

---------------------
4) KARŞILAŞTIRMA
---------------------
x > y
x < y
x == y

---------------------
5) KOŞUL (eger)
---------------------
eger x > y
    yaz "x buyuk"
bitir

eger x == 10
    yaz x*2
bitir

---------------------
6) DÖNGÜ (tekrar)
---------------------
tekrar 3
    yaz "Merhaba"
bitir

tekrar x
    yaz x
bitir

---------------------
7) İÇ İÇE KULLANIM
---------------------
ata x = 5

eger x > 3
    tekrar 2
        yaz x*10
    bitir
bitir

---------------------
8) YORUM SATIRI
---------------------
# bu satir calismaz
# aciklama icin kullanilir

---------------------
9) TAM ORNEK PROGRAM
---------------------
# EMVAT tam ornek

yaz "Program basladi"

ata a = 5
ata b = 3

yaz a+b
yaz a*b

eger a > b
    yaz "a buyuk"
bitir

tekrar 3
    yaz a
bitir

yaz "Program bitti"

---------------------
10) KURALLAR
---------------------
- Her komut satir satir yazilir
- Bloklar MUTLAKA bitir ile kapanir
- Noktali virgul (;) YOK
- { } YOK
- Python / JS kodu YOK
- Sadece EMVAT komutlari

---------------------
11) GECERSIZ ORNEKLER
---------------------
print("merhaba")   -> HATALI
console.log(x)     -> HATALI
x = 5;             -> HATALI
# editör linki
link:https://lattesiber-gurubu.github.io/emvat/emvat.html
