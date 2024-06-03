# PatentSeeker

PatentSeeker, patent arama ve analiz uygulamasıdır. Kullanıcılar basit ve gelişmiş arama seçeneklerini kullanarak patent bilgilerine erişebilir ve bu bilgileri görselleştirilmiş grafikler aracılığıyla analiz edebilir.

## İçindekiler

- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Özellikler

- Basit ve gelişmiş patent arama seçenekleri
- Patent detaylarını görüntüleme
- Teknoloji ve teknik bilgilerini listeleme
- Yıllara göre anahtar kelime kullanımını grafikte gösterme

## Kurulum

### Gereksinimler

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Python 3](https://www.python.org/)
- Gerekli Python kütüphaneleri (aşağıda belirtilmiştir)

### Adımlar

1. Projeyi klonlayın:
    ```bash
    git clone https://github.com/kullanici-adi/PatentSeeker.git
    cd PatentSeeker
    ```

2. Node.js bağımlılıklarını yükleyin:
    ```bash
    npm install
    ```

3. Python için gerekli kütüphaneleri yükleyin:

4. Sunucuyu başlatın:
    ```bash
    node server.js
    ```

5. Python API'yi başlatın (API klasöründe):
    ```bash
    python api.py
    ```

6. Uygulamayı tarayıcınızda açın:
    ```bash
    http://localhost:3008
    ```

## Kullanım

1. **Basit Arama:** Ana sayfada basit arama formunu kullanarak patent başlığına göre arama yapın.
2. **Gelişmiş Arama:** Gelişmiş arama formunu kullanarak başlık, özet, başlangıç ve bitiş tarihlerine göre arama yapın.
3. **Grafikler:** Arama sonuçlarıyla birlikte yıllara göre anahtar kelime kullanım grafiğini görüntüleyin.
4. **Detay Görüntüleme:** Her patentin detaylarını görüntülemek için "Detay" bağlantısına tıklayın.

## Proje Yapısı

- **/public:** Statik dosyalar (CSS, JS, resimler)
- **/views:** EJS şablon dosyaları
- **/routes:** Uygulama rotaları
- **/models:** Veri modelleri
- **/controllers:** İş mantığı ve veri işlemleri
- **server.js:** Uygulamanın ana sunucu dosyası
- **app.py:** Python API sunucu dosyası

## Katkıda Bulunma

Katkıda bulunmak için lütfen bir çekme isteği (pull request) gönderin. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir sorun (issue) açın.

1. Projeyi forklayın.
2. Bir dal (branch) oluşturun: `git checkout -b ozellik-isim`
3. Değişikliklerinizi commitleyin: `git commit -am 'Özellik ekle'`
4. Dalınıza push edin: `git push origin ozellik-isim`
5. Bir çekme isteği (pull request) oluşturun.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.
