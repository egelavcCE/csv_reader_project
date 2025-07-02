# CSV Reader JavaFX Uygulaması

Bu proje, JavaFX kullanılarak geliştirilmiş basit bir CSV dosyası okuma ve haritalama arayüzü sunar. Kullanıcılar, bir CSV dosyasını yükleyip, dosyadaki sütunları belirli alanlara eşleyebilirler. Arayüzde temel olarak bir ana ekran (primary) ve ikincil ekran (secondary) bulunmaktadır.

## Özellikler
- JavaFX tabanlı modern arayüz
- CSV dosyası yükleme (arayüzde buton mevcut, işlevsellik eklenebilir)
- Sütun haritalama için tablo görünümü
- Ekranlar arası geçiş

## Kullanılan Teknolojiler
- Java 11
- JavaFX 13 (javafx-controls, javafx-fxml)
- Maven

## Kurulum
1. **Projeyi klonlayın:**
   ```bash
   git clone <repo-url>
   cd csv_reader_project-public
   ```
2. **Gerekli bağımlılıkları yükleyin:**
   Maven, bağımlılıkları otomatik olarak yönetecektir.
   ```bash
   mvn clean install
   ```
3. **Uygulamayı çalıştırın:**
   ```bash
   mvn javafx:run
   ```

## Proje Yapısı
- `src/main/java/com/example/App.java`: Uygulamanın ana JavaFX başlatıcısı.
- `src/main/java/com/example/controller/PrimaryController.java`: Ana ekranın kontrolcüsü.
- `src/main/java/com/example/controller/SecondaryController.java`: İkincil ekranın kontrolcüsü.
- `src/main/resources/com/example/primary.fxml`: Ana ekran arayüzü.
- `src/main/resources/com/example/secondary.fxml`: İkincil ekran arayüzü.

## Arayüz
- **Üst Menü:** Home, Campaign, Contact, Report, Automation butonları
- **CSV Yükleme:** "Upload a file" butonu (işlevsellik eklenebilir)
- **Sütun Haritalama:** Full Name, First Name, Country, Email Address, Phone başlıklı tablo
- **Onay:** "Confirm" butonu

## Notlar
- Şu anda "Upload a file" ve "Confirm" butonlarının işlevselliği eklenmemiştir. Sadece arayüz olarak mevcuttur.
- Proje, Java 11 ve JavaFX 13 ile uyumludur.

## Lisans
Bu proje eğitim amaçlıdır. 
