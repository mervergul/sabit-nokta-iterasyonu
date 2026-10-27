# Sabit Nokta İterasyonu Çözücü (Fixed-Point Iteration Web GUI)

Bu proje, **Sayısal Analiz** dersi kapsamında geliştirilmiş; kullanıcı dostu bir arayüz üzerinden **Sabit Nokta İterasyonu** (Fixed-Point Iteration) yöntemini uygulayan ve adım adım çözümleri görselleştiren bir web uygulamasıdır.

## 🚀 Özellikler

* **Esnek Girdi Desteği:** Kullanıcılar $f(x)=0$ veya $x=g(x)$ formundaki matematiksel ifadeleri metin olarak girebilir (Math.js kütüphanesi ile *string parsing* yapılır).
* **Parametre Özelleştirme:** Başlangıç değeri ($x_0$), hata toleransı ($e$) ve maksimum iterasyon sayısı ($N_{max}$) dinamik olarak tanımlanabilir.
* **Detaylı İterasyon Tablosu:** AtoZmath formatına benzer şekilde her adım için adım numarası ($k$), $x_k$, $g(x_k)$ ve bağıl hata ($|x_{k+1}-x_k|$) değerlerini listeler.
* **Iraksama ve Hata Yönetimi:** Değerlerin aşırı büyüdüğü ($|g'(x)| \ge 1$), fonksiyonun ıraksadığı veya maksimum iterasyon sayısına ulaşıldığı durumlarda uygulamanın çökmesini engelleyerek kullanıcıya anlaşılır uyarı verir.

## 🛠️ Kullanılan Teknolojiler

* **HTML5 & CSS3:** Responsive ve temiz kullanıcı arayüzü tasarımı.
* **JavaScript (ES6+):** Algoritma mantığı ve dinamik tablo oluşturma.
* **Math.js:** Matematiksel metin ifadelerini ayrıştırma (string parsing) ve hesaplama.

## 💻 Kurulum ve Çalıştırma

Herhangi bir sunucu veya ek kurulum gerektirmez. 
1. Proje dosyalarını indirin.
2. `index.html` dosyasını herhangi bir web tarayıcısında (Chrome, Edge, Firefox vb.) çift tıklayarak çalıştırın.
