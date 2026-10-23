# algoritma-temelleri-alistirmalari
Python öğrenme sürecimde hazırladığım temel algoritma soruları ve çözüm adımları.
🧠 Algoritma Temelleri | Alıştırmalar ve Ödevler

📌 Proje Hakkında

Bu depo, yazılım geliştirme ve Python öğrenme sürecimde algoritmik düşünme ve problem çözme becerilerimi geliştirmek amacıyla hazırladığım çalışmaları içermektedir.

Çalışmalarımda temel matematiksel formülleri, koşullu ifadeleri, döngüleri ve veri işleme mantığını kullanarak çeşitli problemlerin algoritmik çözümlerini oluşturdum.

Bu depo toplam 2 ödev ve 10 algoritma probleminden oluşmaktadır.

---

📚 ÖDEV 1 — Temel Algoritmalar

1. Öğrenci Not Ortalaması Hesaplama

Bir sınıftaki öğrencilerin notlarını kullanarak sınıf ortalamasını hesaplayan ve öğrencilerin durumlarını belirleyen algoritma.

Kullanılan formül:

"Ortalama = Toplam Not / Öğrenci Sayısı"

Algoritma mantığı:

- Öğrenci notları alınır.
- Notların toplamı hesaplanır.
- Ortalama bulunur.
- Her öğrencinin notu ortalamayla karşılaştırılır.
- Ortalamanın altında, üstünde veya eşit olma durumu belirlenir.

Kullanılan kavramlar: Değişkenler, toplama işlemi, karşılaştırma ve koşullu ifadeler.

2. Riskli Sürüş Kontrol Algoritması

Araç hızı ve yakıt seviyesine göre sürüş durumunu kontrol eden algoritma.

Koşul:

"Hız > 100 VE Yakıt < %20"

İki koşul aynı anda sağlanıyorsa "Riskli sürüş", diğer durumlarda "Normal sürüş" mesajı verilir.

Kullanılan kavramlar: Mantıksal VE operatörü, karşılaştırma operatörleri ve if-else mantığı.

3. Serbest Düşme Hızı Hesaplama

Belirli bir yükseklikten serbest bırakılan cismin yere çarpmadan hemen önceki teorik hızını hesaplayan algoritma.

Kullanılan formül:

"v = √(2 × g × h)"

- "v": Hız (m/s)
- "g": Yerçekimi ivmesi (9,81 m/s²)
- "h": Yükseklik (metre)

Bu formül hava direncinin ihmal edildiği ve cismin durgun hâlden bırakıldığı durum için kullanılır.

Kullanılan kavramlar: Matematiksel işlemler, karekök, değişken tanımlama.

4. Mod ve Frekans Hesaplama

Girilen 10 sayı arasından en sık tekrar eden değeri ve tekrar sayısını belirleyen algoritma.

- Mod: En sık tekrar eden değer.
- Frekans: Bir değerin kaç defa tekrar ettiği.

Kullanılan kavramlar: Veri analizi, sayma, karşılaştırma ve tekrar eden değerlerin belirlenmesi.

5. Sayı Tahmin Oyunu

Bilgisayarın 1 ile 50 arasında rastgele seçtiği sayıyı kullanıcının tahmin etmeye çalıştığı algoritma.

Algoritma mantığı:

- Rastgele sayı belirlenir.
- Kullanıcıdan tahmin alınır.
- Tahmin, hedef sayı ile karşılaştırılır.
- Kullanıcıya daha büyük veya daha küçük sayı denemesi söylenir.
- Önceki tahminle karşılaştırılarak "Yaklaştın" veya "Uzaklaştın" geri bildirimi verilir.
- Doğru tahmine kadar işlem tekrarlanır.

Kullanılan kavramlar: Rastgele sayı üretimi, döngüler, koşullu ifadeler ve karşılaştırma.

---

📘 ÖDEV 2 — Matematiksel Algoritmalar

6. Aritmetik Dizi Toplamı

İlk terimi, son terimi ve terim sayısı bilinen aritmetik dizinin toplamını hesaplayan algoritma.

Kullanılan formül:

"S = n × (a₁ + aₙ) / 2"

- "S": Dizinin toplamı
- "n": Terim sayısı
- "a₁": İlk terim
- "aₙ": Son terim

Kullanılan kavramlar: Aritmetik işlemler, değişkenler ve matematiksel formüller.

7. Geometrik Dizi Toplamı

İlk terimi, ortak oranı ve terim sayısı verilen geometrik dizinin toplamını hesaplayan algoritma.

Kullanılan formüller:

Ortak oran 1'e eşit değilse:

"S = a₁ × (1 - rⁿ) / (1 - r)"

Ortak oran 1'e eşitse:

"S = a₁ × n"

- "a₁": İlk terim
- "r": Ortak oran
- "n": Terim sayısı

Kullanılan kavramlar: Üslü sayılar, koşullu ifadeler ve matematiksel hesaplamalar.

8. Kök Ortalama Kare (RMS) Hesaplama

Verilen sayıların karelerinin ortalamasının karekökünü hesaplayan algoritma.

Kullanılan formül:

"RMS = √((x₁² + x₂² + ... + xₙ²) / n)"

Algoritma mantığı:

- Sayılar alınır.
- Her sayının karesi hesaplanır.
- Karelerin toplamı bulunur.
- Toplam, eleman sayısına bölünür.
- Sonucun karekökü hesaplanır.

Kullanılan kavramlar: Döngüler, kare alma, karekök ve ortalama hesaplama.

9. Vektörlerin Skaler Çarpımı

İki vektörün bileşenlerini kullanarak skaler çarpımlarını hesaplayan ve geometrik olarak yorumlayan algoritma.

Kullanılan formül:

"A · B = A₁B₁ + A₂B₂ + ... + AₙBₙ"

Geometrik yorum:

- Sonuç pozitifse vektörler arasındaki açı dardır.
- Sonuç negatifse açı geniştir.
- Sonuç sıfırsa, sıfır olmayan vektörler birbirine diktir.

Kullanılan kavramlar: Vektörler, döngüler, çarpma, toplama ve koşullu ifadeler.

10. Matris Çarpımı

Boyutları uygun olan iki matrisin çarpımını hesaplayan ve sonuç matrisini oluşturan algoritma.

Kullanılan formül:

"C[i,j] = Σ(A[i,k] × B[k,j])"

Burada toplam, "k = 1" değerinden ortak boyut "n" değerine kadar hesaplanır.

Algoritma mantığı:

- Matrislerin boyutları belirlenir.
- Matris elemanları alınır.
- Sonuç matrisi oluşturulur.
- İç içe döngülerle çarpım işlemleri gerçekleştirilir.
- Sonuç matrisi ekrana yazdırılır.

Kullanılan kavramlar: Çok boyutlu diziler, iç içe döngüler ve matris işlemleri.

---

🛠️ Kullanılan Algoritma Yapıları

Yapı| Kullanım amacı
Değişkenler| Verileri saklamak
Koşullu ifadeler| Karar verme işlemleri
Döngüler| Tekrarlanan işlemleri yürütmek
Karşılaştırma operatörleri| Değerleri karşılaştırmak
Matematiksel operatörler| Hesaplama yapmak
Diziler| Birden fazla veriyi işlemek
İç içe döngüler| Matris gibi çok boyutlu işlemleri gerçekleştirmek

🎯 Bu Çalışmalarla Kazanmayı Hedeflediğim Beceriler

- Algoritmik düşünme becerisini geliştirmek.
- Problemleri küçük ve anlaşılır adımlara ayırmak.
- Matematiksel formülleri algoritmalara dönüştürmek.
- Koşullu ifadeleri ve döngüleri doğru kullanmak.
- Python programlamaya sağlam bir temel oluşturmak.
- Farklı problemlere sistematik çözümler geliştirmek.

📂 Depo İçeriği

Bu depoda algoritma çözümlerimin yer aldığı PDF çalışması ve projeyi tanıtan README dosyası bulunmaktadır.

Çözümler, Python kaynak kodu yerine adım adım yazılmış algoritmalar şeklinde hazırlanmıştır.

🚀 Gelişim Sürecim

Yazılım öğrenme yolculuğumun başlangıç aşamasındayım. Temel algoritmaların mantığını öğrenerek Python programlama becerilerimi geliştirmeyi hedefliyorum.

İlerleyen süreçte bu algoritmaları Python kodlarına dönüştürerek depoyu geliştirmeyi planlıyorum.

---

📌 Hazırlayan: Kerem Altungök

💻 Alan: Algoritma ve Programlama Temelleri

📖 Seviye: Başlangıç

