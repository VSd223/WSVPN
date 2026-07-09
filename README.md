<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android_8.0%2B-00FF88?style=for-the-badge&logo=android&logoColor=black" />
  <img src="https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" />
  <img src="https://img.shields.io/badge/Core-Xray%20/%20V2Ray-FF5722?style=for-the-badge&logo=xray&logoColor=white" />
</p>

<h1 align="center">🐈‍⬛ WSVPN — Высокоскоростной VPN-Клиент нового поколения</h1>

<p align="center">
  <b>Легковесный, безопасный и невероятно быстрый клиент для операционной системы Android.</b><br>
  Построен полностью на базе декларативного фреймворка <b>Jetpack Compose</b> и мощного ядра <b>Xray/V2Ray Core</b>.
</p>

---

## ✨ Ключевые возможности

* 🚀 **Мультипротокольная поддержка:** Полноценная работа с конфигурациями **VLESS** (включая REALITY и gRPC), **VMess**, **Trojan**, **Shadowsocks** и **Hysteria/Hysteria2**.
* ⚡ **Авто-балансировщик:** Умный алгоритм, который автоматически анализирует сеть и переключает вас на локацию с наименьшей задержкой на лету.
* 📈 **Мониторинг скорости в реальном времени:** Интегрированные счетчики входящего и исходящего трафика прямо на главном экране во время работы.
* 📶 **Точный мультипробный Ping:** Высокоточный замер сетевого отклика по методу тройного TCP Handshake, защищенный от ложных сетевых колебаний.
* 🔒 **Шифрование подписок:** Поддержка импорта безопасных зашифрованных баз конфигураций (AES-128-ECB) с автоматическим контролем даты истечения доступа.
* 🎮 **Современный Cyberpunk интерфейс:** Темная тема, плавные реактивные переходы, пульсация кнопки подключения и кастомная анимация шкалы сигнала связи при замере пинга.
* 🤖 **Связка с Telegram-ботом:** Нативная интеграция с официальным ботом [@WSVPN_Bobot](https://t.me/WSVPN_Bobot) для мгновенного получения бесплатных ключей доступа.

---

## 🎨 Скриншоты и анимации
> *Здесь вы можете разместить скриншоты вашего интерфейса, анимации подключения и карточек серверов:*

<p align="center">
  <img src="https://images.unsplash.com/photo-1563986768609-322da13575f3?auto=format&fit=crop&w=400&q=80" width="30%" alt="Интерфейс приложения" />
</p>

---

## 🛠 Стек технологий (Tech Stack)

* **UI Layer:** Jetpack Compose (Material 3), Compose Animations
* **Asynchrony:** Kotlin Coroutines, StateFlow, LiveData
* **Core Network:** Xray-core (`libv2ray.aar`), VpnService API
* **Database:** Room Database (для надежного локального хранения добавленных локаций)
* **Encryption:** AES-128 (для безопасной расшифровки VLESS ключей из подписок)
* **Native Build:** Android NDK, CMake (JNI для вызова нативных C++ компонентов защиты)
