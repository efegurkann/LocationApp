# 📍 Location App

Location App, toplu taşıma yolcuları için geliştirilmiş akıllı bir uyku asistanıdır. Varış noktanıza yaklaştığınızda sizi titreşimle uyandırır, böylece gideceğiniz yeri kaçırmazsınız.

## 🚀 Özellikler

- Hedef konuma yaklaşıldığında titreşimli uyarı sistemi
- OpenStreetMap üzerinden kolay varış noktası seçimi
- Arka planda çalışma özelliği ile kesintisiz takip
- Özelleştirilebilir uyarı mesafesi (100m - 500m arası)
- Seyahat geçmişi
- Sık kullanılan konumları kaydetme
- Düşük pil tüketimi için optimize edilmiş sistem
- Türkiye'ye özel adres ve konum araması

## 🎯 Kullanım Senaryoları

- Toplu taşımada seyahat ederken güvenle uyuyabilme
- Uzun yolculuklarda varış noktasını kaçırmama
- Gece seyahatlerinde uyanık kalmaya gerek olmadan yolculuk yapabilme
- Bilmediğiniz güzergahlarda bile rahatlıkla dinlenebilme

## 🛠 Teknolojiler

- React Native
- Expo
- React Navigation
- Expo Location
- React Native Maps
- OpenStreetMap (Nominatim API)
- AsyncStorage
- TypeScript
- Expo Haptics (Titreşim desteği için)
- Expo Task Manager (Arka plan görevleri için)
- Expo Notifications

## 📋 Gereksinimler

- Node.js (v14 veya üzeri)
- npm veya yarn
- Expo CLI
- iOS için Xcode (iOS geliştirmesi için)
- Android için Android Studio (Android geliştirmesi için)

## 🔧 Kurulum

1. Projeyi klonlayın
   ```bash
   git clone [repo-url]
   cd locationapp
   ```

2. Bağımlılıkları yükleyin
   ```bash
   npm install
   ```

3. Uygulamayı başlatın
   ```bash
   npx expo start
   ```

## 📱 Geliştirme

- iOS Simülatör için: `npm run ios`
- Android Emülatör için: `npm run android`
- Web için: `npm run web`

## 🔐 İzinler

Uygulama aşağıdaki izinleri kullanmaktadır:

### Android
- ACCESS_COARSE_LOCATION
- ACCESS_FINE_LOCATION
- ACCESS_BACKGROUND_LOCATION
- FOREGROUND_SERVICE
- VIBRATE
- WAKE_LOCK

### iOS
- NSLocationWhenInUseUsageDescription
- NSLocationAlwaysAndWhenInUseUsageDescription
- NSLocationAlwaysUsageDescription
- Background Modes (Location updates)

## 📝 Önemli Notlar

- Uygulama arka planda çalışırken pil tüketimini optimize etmek için konum güncellemelerini akıllıca yönetir
- Titreşim özelliğinin düzgün çalışması için gerekli izinlerin verildiğinden emin olun
- OpenStreetMap kullanım koşullarına uygun olarak, saniyede 1'den fazla istek atılmamaktadır
- iOS ve Android platformları için gerekli izinlerin yapılandırıldığından emin olun

## ⚠️ Sorumluluk Reddi

Bu uygulama bir yardımcı araçtır ve %100 güvenilirlik garantisi vermez. Kritik seyahatlerinizde yedek alarm sistemleri kullanmanızı öneririz.

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

