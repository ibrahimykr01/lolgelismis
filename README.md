README.md
Aşağıda, geliştirdiğiniz MOBA prototipi için GitHub veya yerel proje dizininizde kullanabileceğiniz kapsamlı bir README.md dosyası bulunmaktadır. Bu dosyayı projenizin ana dizinine README.md adıyla kaydedebilirsiniz.

MOBA Prototipi (HTML5 Canvas)
Bu proje, tarayıcı tabanlı ve çok oyunculu bir MOBA (Çok Oyunculu Çevrimiçi Savaş Arenası) oyununun temel mekaniklerini test etmek amacıyla geliştirilmiş hafif bir prototiptir.

🚀 Projenin Amacı
Projenin temel amacı; oyun döngülerini (game loop), karakter kontrolünü ve dinamik arayüz (UI) öğelerini harici bir oyun motoruna ihtiyaç duymadan, saf web teknolojileriyle (HTML5/Canvas ve JavaScript) optimize bir şekilde çalıştırmaktır.

🛠️ Teknolojiler ve Altyapı
Projeyi çalıştırmak için herhangi bir derleme (build) işlemine gerek yoktur. Kullanılan teknolojiler:

HTML5 Canvas: Karakterlerin ve arayüzün çizimi için.

CSS3: Arayüzün ortalanması ve karanlık tema tasarımı için.

JavaScript (ES6+): Oyun mantığı (hareket, çarpışma, can değerleri).

📋 Özellikler
Dinamik Hareket Sistemi: Farenin harita üzerinde herhangi bir noktasına tıklandığında karakterin oraya yönelmesi.

Sağlık (HP) Barı Göstergesi: Karakterin durumunu anlık olarak yansıtan dinamik bar (yeşil: aktif can, kırmızı: hasar/kayıp).

Optimize Oyun Döngüsü: requestAnimationFrame kullanılarak saniyede 60 kare (60 FPS) yenileme hızı.

Düşük Gecikme / Hafif Yapı: Harici kütüphane gerektirmeyen tek dosya (single-file) mimarisi.

💻 Kurulum ve Çalıştırma
Projenin çalışması için ekstra bir sunucuya veya bağımlılığa ihtiyacınız yoktur.

Bu depoyu bilgisayarınıza klonlayın veya indirin.

Dosya içerisindeki index.html dosyasını herhangi bir modern web tarayıcısında (Chrome, Firefox, Edge vb.) açın.

Karakteri hareket ettirmek için farenizle harita alanına tıklayın.

🗺️ Gelecek Geliştirmeler (Roadmap)
Projenin kapsamını genişletmek için eklenecek bir sonraki modüller:

[ ] Çok Oyunculu Altyapı: Socket.io ile sunucu tabanlı senkronizasyon.

[ ] Minyon ve NPC Sistemi: Koridorlarda otomatik hareket eden yapay zeka birimleri.

[ ] Yetenek (Skill) Mekanikleri: Q, W, E ve R tuşlarına atanabilir animasyonlu vuruşlar ve bekleme süreleri (cooldown).

[ ] Ses Efektleri: Web Audio API ile vuruş ve büyü sesleri entegrasyonu.

🤝 Katkıda Bulunma
Projenin gelişimine katkıda bulunmak için:

Projeyi forklayın.

Yeni bir özellik veya hata düzeltmesi dalı (branch) oluşturun (git checkout -b feature/yetenek-sistemi).

Değişikliklerinizi commit edin (git commit -m 'Yeni özellik: Yetenek eklendi').

Dalınızı ana depoya gönderin (git push origin feature/yetenek-sistemi).

📜 Lisans
Bu proje MIT lisansı ile lisanslanmıştır. Detaylar için LICENSE dosyasına göz atabilirsiniz.
