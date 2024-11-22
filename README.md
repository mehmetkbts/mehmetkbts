# Sinema Yönetim Sistemi

Bu proje, bir sinema salonunda film izleme, müşteri kaydetme, seans saatleri ekleme, ödeme yapma ve müşteri bilgilerini görüntüleme gibi işlemleri simüle eden bir sinema yönetim sistemidir. Java dilinde yazılmıştır ve nesne yönelimli programlama (OOP) ilkelerini kullanır.

## Özellikler

- **Film Yönetimi**: Film ekleme, seans ekleme ve film bilgilerini gösterme.
- **Salon Yönetimi**: Film salonu ekleme, koltuk durumu kontrolü ve müşteri kaydetme.
- **Müşteri Yönetimi**: Müşteri bilgileri (ad, soyad, telefon, yiyecek, içecek, koltuk numarası) girişi, ödeme işlemi ve film izleme simülasyonu.
- **Polimorfizm**: Farklı sınıflarda ortak metot kullanımı (örneğin, `BilgiGoster` metodu).

## Kurulum ve Kullanım

1. **Proje Dosyalarını İndirin**
   - Bu projeyi GitHub üzerinden indirip yerel bilgisayarınıza kaydedebilirsiniz.

2. **IDE veya Komut Satırı ile Çalıştırma**
   - **Eclipse**, **IntelliJ IDEA** gibi bir IDE veya terminal kullanarak Java kodunu çalıştırabilirsiniz.
   - Terminal üzerinden çalıştırmak için aşağıdaki komutları kullanabilirsiniz:
     ```bash
     javac Main.java
     java Main
     ```

3. **Çalıştırma Adımları**
   - Programı çalıştırdığınızda bir dizi menü ile karşılaşacaksınız.
   - Kullanıcı, film ve salon seçimi, seans saati seçimi, müşteri bilgileri girişi, koltuk seçimi ve ödeme işlemleri gibi adımları takip edebilir.

4. **Menü Seçenekleri**
   - **1. Film ve Salon Seçme**: Kullanıcı bir film seçip, seans saati belirler, ardından müşteri bilgilerini girer ve ödeme işlemi yapar.
   - **2. Müşteri Silme**: Salon A'da kayıtlı olan müşterilerin listelenmesi ve ardından bir müşterinin silinmesi.
   - **3. Çıkış**: Programdan çıkış yapılır.

## Sınıflar

- **BaseEntity**: Tüm sınıfların ortak özelliklerini taşıyan temel sınıf.
- **Film**: Film bilgilerini (isim, tür, süre) ve seans saatlerini tutar.
- **Musteri**: Müşteri bilgilerini ve ödemeyi içerir. Aynı zamanda film izleme ve koltuk güncelleme gibi işlemleri gerçekleştirir.
- **Salon**: Salon bilgilerini ve salonun içindeki filmleri ve müşterileri yönetir.

## Yazarlar
https://github.com/mehmetkbts
