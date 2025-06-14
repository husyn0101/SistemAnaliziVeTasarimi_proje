# SistemAnaliziVeTasarimi_proje
Hastane Randevu Sistemi Prtojesi Google Drive Linki:  https://drive.google.com/drive/folders/15Ro6ZZcVBcznpashKaCgygZdlAD1Yh1q?usp=drive_link

# Hastane Randevu Sistemleri

## Proje Hakkında
Bu proje, Visual Studio 2022 kullanılarak geliştirilmiş bir *Hastane Randevu Yönetim Sistemi* uygulamasıdır. Projenin amacı, hastane ortamında doktorların, hastaların, kliniklerin ve randevuların etkin ve düzenli şekilde yönetilmesini sağlamaktır. Kullanıcı dostu arayüzleri ile hastane çalışanları ve yöneticiler, hastaların randevu işlemlerini kolayca gerçekleştirebilir.

## Teknolojiler
- *Programlama Dili:* C#  
- *Geliştirme Ortamı:* Visual Studio 2022  
- *Veritabanı:* SQLite (DB Browser for SQLite ile yönetildi)

## Veritabanı Tasarımı
Projede kullanılan ana tablolar ve içerikleri:

| Tablo Adı  | Alanlar                         | Açıklama                       |
|------------|--------------------------------|-------------------------------|
| Doktorlar  | DoktorID, DoktorAdi, KlinikAdi, DoktorSoyadi | Doktor bilgileri               |
| Hastalar   | TC, Ad, Soyad, Cinsiyet, KanGrubu, Telefon, Email, Adres | Hasta bilgileri                |
| Klinikler  | KlinikID, KlinikAdi             | Klinik bilgileri               |
| Randevular | RandevuID, TC, DoktorAdi, Tarih, Saat, KlinikAdi | Hasta randevu bilgileri        |

## Proje Formları ve İşlevleri
- *DoktorForm:* Doktor bilgileri yönetimi  
- *FormHastaKayit:* Yeni hasta kaydı (INSERT işlemi)  
- *FormDoktorPanel:* Doktorların görüntülenmesi ve sorgulanması (SELECT işlemi)  
- *YoneticiAnaForm:* Randevular üzerinde güncelleme (UPDATE) ve silme (DELETE) işlemleri  
- *FormHastaPanel, FormHastaRandevuPanel, FormYoneticiPanel, Form1:* Kullanıcı ve yönetici panelleri

## Özellikler
- Hasta kayıt işlemleri  
- Doktorların ve kliniklerin yönetimi  
- Randevu oluşturma, güncelleme ve silme  
- Kullanıcı dostu arayüz  

## Kurulum ve Çalıştırma
1. Projeyi klonlayın veya ZIP olarak indirin.  
2. Visual Studio 2022 ile projeyi açın.  
3. SQLite veritabanı dosyasını DB Browser for SQLite ile açabilir, tablo ve verileri inceleyebilirsiniz.  
4. Projeyi derleyip çalıştırarak form ekranlarından işlemlerinizi gerçekleştirebilirsiniz.

## Proje Sahibi
Hüseyin Can Şeref
225511060
