# Fiyat Takip Uygulaması
Fiyat Takip Uygulaması, Windows Forms (C#) ile geliştirilen, kullanıcıların finansal bilgilerini güncel olarak görüntülemesini ve manuel olarak veri girmesini sağlayan bir masaüstü uygulamasıdır.
# Geliştirme aşamasında olan bir proje %25






![Ekran görüntüsü 2025-06-03 161026](https://github.com/user-attachments/assets/1234fd02-eb73-4374-8222-4f2cc1286b94)


![Ekran görüntüsü 2025-06-03 160953](https://github.com/user-attachments/assets/ccd56400-2c90-4a9b-a5f4-803805c9c6eb)


#  Özellikler<br>


 Grafik Görselleştirme:<br>
Haftalık, aylık ve yıllık altın fiyatları LiveCharts ile çizgi grafik olarak görüntülenir.<br>

 Manuel Veri Girişi:<br>
Kullanıcılar tarih, çeyrek, gram ve tam altın fiyatlarını manuel olarak girebilir.<br>

 TCMB'den Anlık Veri Çekme:<br>
Uygulama açıldığında Türkiye Cumhuriyet Merkez Bankası'nın XML API'sinden veri çeker. Veri alınamazsa, rastgele verilerle grafik çizilir ve kullanıcı bilgilendirilir.<br>

 Veri Kaydetme (Opsiyonel):<br>
İleride veri kaydetme/dosyaya yazma veya veritabanı desteği kolayca eklenebilir.<br>


#  Kurulum ve Kullanım

Bu projeyi klonlayın:   git clone https://github.com/kullaniciadi/FiyatTakipUygulamasi.git
LiveCharts.WinForms paketini yükleyin:  Install-Package LiveCharts.WinForms



#  Geliştirici Notları
Grafikler LiveCharts.WinForms ile çizilir.

Gerçek veriler TCMB'nin döviz XML servisinden alınır:
https://www.tcmb.gov.tr/kurlar/today.xml

Veri alınamazsa uygulama otomatik olarak 7 günlük rastgele fiyat verisi üretir ve kullanıcıyı bilgilendirir.




#  Gelecek Geliştirmeler
 SQL veya JSON dosya tabanlı veri kaydı

 Tarih aralığına göre filtreleme

 Fiyat trendi analizi

 Dark/Light tema seçeneği





