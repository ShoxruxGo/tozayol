# TozaYo‘l · Toshkent 🍃

Toshkent shahri havo sifati, transport oqimi va ekologik taʼsirni modellashtiruvchi interaktiv veb-platforma.

## 🚀 Loyiha haqida

**TozaYo‘l** — shahar havosi sifatini real vaqt rejimida kuzatish, transport emissiyasining atmosferada tarqalishini fizik tenglamalar asosida modellashtirish va turli ekologik siyosatlar samarasini hisoblash imkonini beruvchi yagona interaktiv taqdimot va simulyatsiya tizimi.

### Asosiy imkoniyatlar:
- 🛰 **Jonli meteorologiya va havo sifati:** Open-Meteo va Copernicus CAMS API orqali Toshkentning so‘nggi 60 kunlik haqiqiy maʼlumotlari hamda hozirgi harorat, shamol va $\text{PM}_{2.5}, \text{NO}_2, \text{CO}$ darajalari.
- 🚗 **Real vaqt transport simulyatsiyasi:** Toshkent shahar markazi va asosiy magistral ko‘chalari bo‘ylab turli transport vositalari harakati (benzin, metan, propan, Damas, elektrobus, yuk mashinalari, EV).
- 🌪 **Adveksiya-diffuziya modeli:** Shamol tezligi va atmosferaning barqarorlik sinfiga bog‘liq differensial tenglamalar (PDE) orqali tutun tarqalishini vizuallashtirish.
- 🤖 **AI prognoz moduli:** O‘tgan davr maʼlumotlari asosida gradient boosting modeli yordamida keyingi 24 soatlik ifloslanish darajasini oldindan aytish.
- 📊 **Ekologik chora-tadbirlar kalkulyatori:** Jamoat transportini rivojlantirish, kam emissiyali zonalar (LEZ), yashil polosalar kabi yechimlarning havoga taʼsirini hisoblash.

## 🛠 Texnologiyalar
- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Xaritalar:** Leaflet.js, OpenStreetMap
- **Formulalar:** KaTeX
- **API integratsiyalari:** Open-Meteo Air Quality & Weather API, Copernicus CAMS

## 🌐 Deploy qilish (Vercel)

Loyiha to‘liq statik formatda tayyorlangan bo‘lib, Vercel’ga 1 ta tugma bilan ulanadi:
1. Vercel dashboardiga kiring.
2. Ushbu GitHub repozitoriyani import qiling (`Add New... -> Project`).
3. Hech qanday build buyrug‘i kerak emas (`Other` / static).
4. **Deploy** tugmasini bosing.
