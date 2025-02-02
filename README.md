# 📍 Location App

Bu uygulama, React Native ve Expo kullanılarak geliştirilmiş bir konum takip uygulamasıdır.

## 🚀 Özellikler

- Gerçek zamanlı konum takibi
- Harita üzerinde görselleştirme
- Konum geçmişi
- Bildirimler
- Arka planda konum takibi

## 🛠 Teknolojiler

- React Native
- Expo
- React Navigation
- Expo Location
- React Native Maps
- AsyncStorage
- TypeScript

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

3. Gerekli ortam değişkenlerini ayarlayın
   - `.env.example` dosyasını `.env` olarak kopyalayın
   - Gerekli API anahtarlarını ekleyin

4. Uygulamayı başlatın
   ```bash
   npx expo start
   ```

## 📱 Geliştirme

- iOS Simülatör için: `npm run ios`
- Android Emülatör için: `npm run android`
- Web için: `npm run web`

## 🔑 Ortam Değişkenleri

Aşağıdaki ortam değişkenlerinin `.env` dosyasında tanımlanması gerekmektedir:

```
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

## 📝 Notlar

- Uygulamayı production ortamına almadan önce tüm API anahtarlarının güvenli bir şekilde saklandığından emin olun
- Arka plan konum izinlerinin kullanıcı tarafından verildiğinden emin olun
- iOS ve Android platformları için gerekli izinlerin yapılandırıldığından emin olun

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

## 📞 İletişim

Proje Sahibi - [@github_username](https://github.com/github_username)

Proje Linki: [https://github.com/github_username/locationapp](https://github.com/github_username/locationapp)
