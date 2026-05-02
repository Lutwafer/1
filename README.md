# FitCoach Pro — UI как на скриншоте

Готовый архив со светлым мобильным UI:
- верхние вкладки
- карточка программы
- список следующих тренировок
- блок уведомлений
- нижнее меню
- Firebase Auth / Firestore
- Paywall / PRO
- Demo режим

## Как запустить
Открой `index.html`.

## Как подключить Firebase
1. Firebase Console → Create project
2. Add app → Web
3. Скопируй firebaseConfig
4. Вставь в `js/config.js`
5. Authentication → Email/Password → Enable
6. Firestore Database → Create database

## PRO / оплата
В `js/config.js` вставь Stripe Payment Link:
```js
const STRIPE_PAYMENT_LINK = "https://buy.stripe.com/...";
```

DEMO PRO работает кнопкой `Активировать DEMO PRO`.
