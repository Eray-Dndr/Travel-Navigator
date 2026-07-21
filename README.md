# Travel Navigator

Travel Navigator, React Native ve Expo kullanarak geliştirdiğim bir mobil uygulamadır. Uygulama, React Navigation kullanılarak oluşturulmuş çok sayfalı bir yapıya sahiptir. Kullanıcı ana ekrandan farklı şehirleri seçebilir, seçilen şehre ait bilgileri detay ekranında görüntüleyebilir ve uygulama içerisindeki diğer sayfalar arasında geçiş yapabilir.

## Özellikler

* Çok sayfalı mobil uygulama
* Stack Navigation kullanımı
* Bottom Tab Navigation kullanımı
* Sayfalar arasında veri aktarımı
* Dinamik detay ekranı
* Geri dönüş (Back) navigasyonu

## Kullanılan Teknolojiler

* React Native
* Expo
* React Navigation
* JavaScript

## Proje Yapısı

```text
travel-navigator
│
├── assets/
├── screens/
│   ├── HomeScreen.js
│   ├── DetailsScreen.js
│   └── SettingsScreen.js
│
├── App.js
├── index.js
├── package.json
└── app.json
```

## Kurulum

Projeyi klonladıktan sonra aşağıdaki komutları çalıştırabilirsiniz.

```bash
npm install
npx expo start
```

Uygulamayı Expo Go veya Android Emulator üzerinden çalıştırabilirsiniz.

## Kullandığım Yapılar

* React Navigation
* Native Stack Navigator
* Bottom Tab Navigator
* Screen Components
* Navigation Props
* Route Params
* `navigate()`
* `goBack()`
* React Native Components
