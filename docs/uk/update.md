---
title: Новини та оновлення OpenIPC FPV
description: Останні новини, оновлення прошивок та нові можливості системи OpenIPC FPV для покращення FPV-польотів
---

# Оновлення OpenIPC FPV 

## Веб-інтерфейс для налаштування камери 

---

📅 Дата: 25 квітня 2025 року  
<p> З останніми оновленнями прошивок **Air Unit'ів** було додано підтримку **WebUI інтерфейсу**, що дозволяє отримати доступ до налаштувань камери напряму через браузер.</p>  
➡️ **Для цього спочатку необхідно оновити прошивку вашої камери.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/JzGqK7jw-To?si=-GH2XBDmUU7vAA6D" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Доступ до інтерфейсу

Відкрийте один із наступних адрес у браузері:

- [http://openipc.local](http://openipc.local)
- [http://192.168.1.10](http://192.168.1.10)

Дані для входу

- **Ім’я користувача:** `root`  
- **Пароль:** `12345`

---

Перший вхід

Під час першого входу система запропонує повторно ввести пароль. Після цього він буде збережений для надання повного доступу до веб-інтерфейсу камери.

> 📌 Рекомендується змінити пароль після першого входу для забезпечення безпеки (12345).


---

## Jumbo Frame — розширений пакет рейту до 50 Мбіт/с

📅 Дата: 23 квітня 2025 року  

<p>У квітні 2025 року в OpenIPC було додано підтримку **Jumbo Frame** у WFB-ng, що дозволяє передавати відео з бітрейтом до **50 Мбіт/с**.</p>

Це дає змогу отримати ще чіткіше зображення та стабільніший відеопотік під час FPV-польотів.

**Як активувати:**
- через OpenIPC Configurator Mario
- або вручну: у файлі `wfb.yaml` змінити параметри jumbo packet rate

---

Сумісність

**За результатами тестів автора:**

- Jumbo Frame працює на частоті **40 МГц**
- Підтримується лише з мережевими картами **RTL8812AU**

**За результатами тестів авторів OpenFPV:**

- Jumbo Frame працює на частоті **20 МГц** до 30 Мбіт/с
- Підтримується з мережевими картами **RTL8812EU2**


---


Корисні посилання

- [Інструкція з налаштування Jumbo Frame](https://www.youtube.com/watch?v=dGQFa9v9YkI)
- [GitHub – OpenIPC Configurator](https://github.com/OpenIPC/configurator)
- [Огляд оновлення на YouTube](https://www.youtube.com/watch?v=z-SMy0QHJwk)

---

> ❗️Це оновлення вже інтегроване в документацію на [openfpv.com.ua](https://openfpv.com.ua). Якщо ви хочете протестувати нові функції — оновіть прошивку до останньої версії через Multiconfigurator або Mario Configurator.
