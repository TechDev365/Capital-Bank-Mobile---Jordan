<p align="center">
  <img src="https://play-lh.googleusercontent.com/w4fqrKmsqXFabB9t5wTbL1xdxWsF_zCZbKs8A3_AfASQFNX19yxpzkbuVZ8Og5Wraj8=w240-h480-rw" width="120" style="border-radius: 20px;" alt="Capital Bank App Logo" />
</p>

<h1 align="center">💰 Capital Bank of Jordan – Digital Banking</h1>

<p align="center"><em>"Your financial world, simplified."</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4417bf8b-58f6-4aa6-b911-3b90ca1e391c" width="400" style="border-radius: 60px;"  />
</p>

---

### 📲 Available On


<a href="https://play.google.com/store/apps/details?id=com.capital.cbt&hl=en">
   <img height="80" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play"/>
</a>


---

### 🧰 Built With

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/65dea6c4eaca7da319e552c09f4cf5a9a8dab2c8/icons/Dart-Dark.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-plain-wordmark.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/65dea6c4eaca7da319e552c09f4cf5a9a8dab2c8/icons/Figma-Dark.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/LelouchFR/skill-icons/main/assets/apple-auto.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original-wordmark.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="40" height="40"/>
</p>

---

## 🗂️ Project Structure

<pre>
  lib/
├── base/ # Base architecture: page, viewModel, widget
├── di/ # Dependency injection
│ ├── app/
│ ├── bill_payment/
│ └── apple_pay/
├── feature/ # Business logic & screens
│ ├── apple_pay/
│ │ ├── apple_pay_error/
│ │ ├── apple_pay_info/
│ │ ├── apple_pay_successful/
│ │ └── verify_mobile/
│ ├── bill_payment/
│ ├── credit_card_setting/
│ └── application_features/
├── l10n/ # Localization
├── main/ # App entry + routing
│ └── navigation/
├── ui/ # UI components (molecules, atoms, etc.)
├── utils/ # Utilities (parsers, formatters, extensions)
│ ├── parser/
│ └── extensions/
├── validation/ # Input validation & business rules
├── main.dart # Entry point
└── test_app_pay.dart # Payment test harness
</pre>

---

## 🧱 Architecture

- **MVVM**: View, ViewModel, Model separation
- **Clean Architecture** principles with `di`, `feature`, `utils`, and layered domain logic
- **Scalable module-based approach**: Apple Pay, Bill Payments, etc.
- **Localization** via `.arb` in `l10n/`
- **Navigation** with centralized routing

---

## ✨ Key Highlights

### 📍 Goal-Oriented Development
> Developed to simplify mobile banking while delivering a secure and intuitive digital experience.

### 🛡️ Security First
> Multi-layered security (e.g., secure login, encrypted transactions, biometric support)

### 📱 Modern UX
> Designed with Figma and implemented via Flutter widgets

### 🤝 Agile Collaboration
> Built in partnership with Capital Bank using Agile, CI/CD & regular sprints.

---

## 📷 App Screenshots

 ![Real-time Insights](https://play-lh.googleusercontent.com/Kc6tRzjkpU_3Z6RQmsHn6M7hit_6xNJ042965GbjQHqG85CQ5Eu19tC1MHd1rbLoJg=w526-h296-rw)  ![Enhanced Security](https://play-lh.googleusercontent.com/tB1yklWVjoiF2CsEOVTu1MsqhMTBJB8bdGcxpUfHH1DAHk3n8HQf9xqxsVTXCuT2KwK-=w526-h296-rw)  ![Branch & ATM Locator](https://play-lh.googleusercontent.com/OvAoB1mcnB5a9N-Hapgh4OAEnu6O-Y0m6gkhiZ4K_1HsV4Cuc4zw3VTTQNCvY8EF_2Y=w526-h296-rw)  ![Customer Support](https://play-lh.googleusercontent.com/IPv3ao-lTz2wblSjg9zw2kmp6W31kV_WoG-kPgUIHlX_5a6au01l5WQ_d6EGuB8YuXU=w526-h296-rw) 

---

## 📊 App Stats

| Platform             | Rating            | Downloads       |
|----------------------|-------------------|-----------------|
| 📱 **Google Play Store** | ⭐️⭐️⭐️⭐️⭐️ (4.5) | 100K+ downloads |

---

## 🔐 Features

- ✅ **Account Overview**: Balances, transaction history
- ✅ **Transfers**: Local & international
- ✅ **Bill Payments**: Predefined & custom
- ✅ **Apple Pay Integration**
- ✅ **Biometric Login (FaceID/TouchID)**
- ✅ **Card Management**: Block/unblock, set limits
- ✅ **ATM & Branch Locator**
- ✅ **24/7 In-App Support**

---
