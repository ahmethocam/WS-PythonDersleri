# Pythonda Değişken Kavramı

Python'da değişkenler, bilgisayar belleğinde belirli bir veriyi saklamak için kullanılan etiketler gibidir. Bu etiketler sayesinde, programımızın farklı yerlerinde bu veriye kolayca erişebilir ve üzerinde değişiklikler yapabiliriz.

Değişken Tanımlama
Python'da bir değişkeni tanımlamak için, değişkenin adını eşitlik (=) işareti ile takip eden bir değer ataması yaparız.


<code-block lang="python">
# Bir tamsayı değişkeni
sayi = 10
# Bir metin (string) değişkeni
metin = "Merhaba, Python!"
# Bir ondalıklı sayı (float) değişkeni
pi = 3.14
</code-block>

Kodu dikkatli kullanın.

# Değişken Adlandırma Kuralları
1. Harf veya alt çizgi ile başlamalı: sayi, metin, my_variable gibi.
2. Rakam içerebilir ancak rakamla başlayamaz: sayi2, metin3 gibi.
3. Büyük küçük harf duyarlıdır: sayi ve Sayi farklı değişkenlerdir.
4. Özel karakterler kullanılamaz: !, @, # gibi.
5. Anahtar kelimeler (komutlar) kullanılamaz: if, else, for gibi.

# Değişken Türleri

Python, dinamik olarak tip belirleme özelliğine sahiptir. Yani, bir değişkene atadığınız değeğe göre otomatik olarak bir veri tipi belirlenir.

- int: Tamsayılar (örneğin: 5, -2, 0)
- float: Ondalıklı sayılar (örneğin: 3.14, -2.5)
- str: Metinler (örneğin: "Merhaba", 'Python')
- bool: Mantıksal değerler (True veya False)

# Değişkenlerin Kullanımı
1. <b>Değer atama:</b> 

Bir değişkene yeni bir değer atayarak içeriğini değiştirebilirsiniz.

<code-block lang="python">
isim = "Mehmet"
yas = 19
dogumYili = 2012
# Aynı değişkene daha sonradan yeniden değer atayabilirsiniz. 
# Son atanan değer artık işlem görecektir.
isim = "Zeynep"
print(isim)
</code-block>

<code>
Çıktı:
Zeynep
</code>

<b>Hesaplama:</b>

Değişkenleri matematiksel işlemlerde kullanabilirsiniz.

<code-block lang="Python">
a = 10
b = 20
sonuc = a + b
print(sonuc)
</code-block>

<code>
Çıktı:
30
</code>

<b>Karşılaştırma:</b>

Değişkenleri karşılaştırma işlemlerinde kullanabilirsiniz.

<code-block lang="python">
yas = 19
kayitYasi = 18
if yas > kayitYasi:
    print("Kayıt yaptırabilir")
else:
    print("Kayıt yaptıramaz")
</code-block>

<b>Veri yapılarına ekleme:</b>

Değişkenleri liste, sözlük gibi veri yapılarına ekleyebilirsiniz.

<code-block lang="python">
# diziler
a = 5
b = 10
sayilar = [1, 2, 3, 4, a, 6, 7, 8, 9, b]
# Tuple (Demetler)
gun3 = "Çarşamba"
gun5 = "Cuma"
gunler = ("Pazartesi", "Salı", gun3, "Perşembe", gun5, "Cumartesi", "Pazar")
# Dictionary
isim = "Mehmet"
soyisim = "Yılmaz"
okulno = 123
ogrenciBilgileri = {
    "adi":isim,
    "soyadi":soyisim,
    "okulnumarasi":okulno
    }
</code-block>
