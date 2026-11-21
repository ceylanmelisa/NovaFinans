# NovaFinans

NovaFinans, HTML, CSS ve JavaScript ile hazırladığım kişisel finans paneli çalışmasıdır. Projede form kullanımı, responsive tasarım, DOM işlemleri ve tarayıcıda veri saklama konularını uyguladım.

## Özellikler

- Giriş ve kayıt sayfaları
- Şifre tekrarı kontrolü
- Gelir, gider ve hesap hareketlerini gösteren örnek panel
- Dört farklı renk teması
- Kartları sürükleyerek sıralama, kaldırma ve yeniden ekleme
- Panel sütun sayısını değiştirme
- Kullanıcı adı, tema ve panel düzenini `localStorage` ile saklama

## Dosyalar

- `index.html`: Giriş sayfası
- `register.html`: Kayıt sayfası ve form kontrolleri
- `dashboard.html`: Finans paneli ve panel ayarları

## Çalıştırma

Kurulum gerekmiyor. `index.html` dosyasını tarayıcıda açmak yeterli.

## Nasıl çalışıyor?

Kayıt formu gönderildiğinde iki şifrenin aynı olup olmadığı kontrol edilir. Kullanıcının adı `localStorage` alanına yazılır ve panel açıldığında buradan okunur. Tema, sütun sayısı, kart sırası ve gizlenen kartlar da aynı yöntemle tarayıcıda saklanır.

Bu proje bir arayüz çalışmasıdır. Gerçek bir sunucuya veya banka servisine bağlı değildir; paneldeki finans bilgileri örnek veridir.
