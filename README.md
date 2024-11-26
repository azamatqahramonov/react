## Node js

Node.js — bu JavaScript kodlarini server tomonida ishlatishga imkon beruvchi muhit (runtime environment). Node.js yordamida JavaScriptni faqat brauzerda emas, balki serverda ham ishlatishingiz mumkin.

Node.js quyidagi asosiy xususiyatlarga ega:

V8 JavaScript dvigateli: Node.js, Google Chrome'dagi JavaScript V8 dvigatelini ishlatadi, bu tezlik va samaradorlikni ta'minlaydi.

Asinxron va hodisaga asoslangan (Event-driven): Node.js asinxron yondashuvni qo'llab-quvvatlaydi, bu esa resurslar bilan ishlashda samaradorlikni oshiradi. Bu model serverni samarali ishlatishga imkon beradi, ayniqsa ko'p so'rovlar bo'lsa.

NPM (Node Package Manager): Node.js uchun keng ko'lamli paketlar va kutubxonalar mavjud bo'lgan NPM (Node.js Package Manager) tizimi bilan birga keladi. Bu tizimni foydalanish orqali siz dasturga kerakli kutubxonalarni osongina o'rnatishingiz mumkin.

Tez va samarali: Node.js, ayniqsa, I/O (Input/Output) bilan bog'liq operatsiyalarni amalga oshiradigan dasturlar uchun juda mos keladi, chunki u bloklovchi bo'lmagan va samarali ishlov berishni ta'minlaydi.

Node.js odatda veb-serverlar, REST API'lar, real vaqtda ishlov berish tizimlari, chat dasturlari, fayl uzatish va ko'p foydalanuvchilar bilan ishlov beradigan ilovalar uchun ishlatiladi.]

## React

React — bu foydalanuvchi interfeyslarini (UI) yaratish uchun ishlatiladigan JavaScript kutubxonasi. Uni 2013-yilda Facebook yaratgan va hozirda ochiq manba sifatida ishlab chiqilmoqda. React yordamida siz dinamik va interaktiv veb-ilovalar yaratishingiz mumkin, ayniqsa ko'plab foydalanuvchi o'zgarishlari va real-vaqt yangilanishlarini talab qiladigan ilovalar uchun juda mos keladi.

React'ning Asosiy Xususiyatlari:
Component-Based Architecture (Komponentga Asoslangan Arxitektura): React komponentlar yordamida foydalanuvchi interfeysini yaratishga imkon beradi. Har bir komponent o'zining mustaqil, qayta ishlatiladigan qismidir. Komponentlar yuqori darajadagi (parent) yoki pastki darajadagi (child) bo'lishi mumkin va ular o'rtasida ma'lumot uzatish mumkin.

Virtual DOM (Virtualizatsiya qilingan DOM): React o'zining Virtual DOM (Document Object Model) texnologiyasini ishlatadi. Virtual DOM haqiqiy DOM bilan solishtirganda juda tez ishlaydi, chunki o'zgartirishlar avval Virtual DOM'da amalga oshiriladi, keyin esa haqiqiy DOM yangilanadi. Bu usul ishlash samaradorligini oshiradi va ilovalar tezligini yaxshilaydi.

Declarative Syntax (Deklarativ Sintaksis): React deklarativ yondashuvni qo'llab-quvvatlaydi. Bu demak, siz React komponentlarini yaratishda qanday natija ko'rishni ta'riflashga e'tibor qaratishingiz kerak, React esa o'z navbatida bu natijani qanday olishni hal qiladi. Bu sizga kodni toza va o'qilishi oson qilish imkonini beradi.

JSX (JavaScript XML): JSX — bu JavaScript va HTML sintaksisining kombinatsiyasi bo'lib, React'ga xos bo'lgan sintaksisdir. JSX yordamida siz HTML kodini JavaScript faylida yozishingiz mumkin. Bu dasturchilarga UI yaratishda yaxshiroq va tezroq ishlash imkonini beradi.


Unidirectional Data Flow (Bitta Yo'nalishda Ma'lumotlar Oqimi): React'da ma'lumotlar faqat bitta yo'nalishda (parentdan childgacha) oqadi. Bu yondashuvni ma'lumotlar oqimi nazorat qilishni osonlashtiradi va ilovaning holatini boshqarish uchun samarali usulni taqdim etadi.

Hooks: React 16.8 versiyasidan boshlab Hooks qo'shildi, bu esa funksional komponentlarda holatni (state) va boshqa xususiyatlarni ishlatish imkonini beradi. Hooks yordamida siz holatni, tomonlar (side effects), kontekstlarni va boshqa imkoniyatlarni faqat funksional komponentlar ichida ishlatishingiz mumkin.

React Router: React ilovalarida sahifalar o'rtasida navigatsiyani ta'minlash uchun React Router kutubxonasi ishlatiladi. U yordamida bir sahifali ilovalar (Single Page Applications) yaratish mumkin, bu esa foydalanuvchi tajribasini yaxshilaydi.

State Management (Holatni Boshqarish): React o'zining useState hook'ini va boshqa holatni boshqarish usullarini taqdim etadi. Ammo, katta ilovalarda holatni boshqarish yanada murakkablashadi. Bunday holatlarda Redux yoki Context API kabi kutubxonalar ishlatiladi.

React'ning Afzalliklari:
Tez ishlash: Virtual DOM yordamida React UI'ni tez va samarali yangilaydi.

Qayta ishlatish: Komponentlarning qayta ishlatilishi ilovaning kodini optimallashtiradi va o'qilishi oson qiladi.

Keng jamoa va qo'llab-quvvatlash: React — eng ommabop JavaScript kutubxonalardan biri, va keng qo'llab-quvvatlashga ega jamoa mavjud.

Oson o'rganish: React'ning soddaligi va komponentlarga asoslangan yondashuvi uni yangi boshlovchilar uchun ham oson o'rganishga imkon beradi.

Keng kutubxonalar va vositalar: React uchun juda ko'p kutubxonalar va vositalar mavjud (Redux, React Router, Material-UI, va boshqalar), bu esa ilovalarni ishlab chiqishni osonlashtiradi.

React'ni Qayerda Ishlatish mumkin?
Bir sahifali ilovalar (SPA): React yordamida foydalanuvchi o'zaro aloqalarini real vaqt rejimida yangilashni talab qiladigan ilovalar yaratish mumkin.
Mobil ilovalar: React Native yordamida React bilan mobil ilovalar ishlab chiqish mumkin.
Server tomoni renderlash (SSR): React, Next.js kabi ramkalar yordamida serverda render qilishni qo'llab-quvvatlaydi.

## API

React API — bu React kutubxonasining ichida mavjud bo'lgan metodlar, funksiyalar va obyektlar to'plamidir, ular React ilovalarini yaratish va boshqarish uchun ishlatiladi. React API yordamida komponentlar yaratish, holatni boshqarish, foydalanuvchi o'zgarishlariga javob berish va boshqa funksiyalarni amalga oshirish mumkin.

React API ning asosiy qismlari:
React.createElement: JSX sintaksisi React'ga tushunarli bo'lishi uchun, React.createElement() metodidan foydalanadi. Bu metod HTML elementlarini yaratish uchun ishlatiladi.

Component: React'ning asosiy qurilish bloklari bo'lgan komponentlarni yaratish uchun React.Component yoki function komponentlardan foydalaniladi.

useState: Funksional komponentlarda holatni (state) boshqarish uchun ishlatiladi.

useEffect: Asinxron operatsiyalarni amalga oshirish yoki komponentning hayotiy tsiklini boshqarish uchun ishlatiladi (masalan, ma'lumotlarni olish).

useContext: Global holatni boshqarish va ma'lumotlarni komponentlar o'rtasida uzatish uchun ishlatiladi.

React Router: Sahifalar o'rtasida navigatsiya qilish uchun foydalaniladigan kutubxona.

ReactDOM.render: Komponentlarni DOM'ga render qilish uchun ishlatiladi (faqat React 17 va undan oldin).

React.Fragment: Bir nechta elementni bitta qadoqlovchi komponentga o'rash uchun ishlatiladi, lekin u DOM'ga hech qanday qo'shimcha element qo'shmaydi.

React API — bu React bilan ishlashda barcha zaruriy funktsiyalarni o'z ichiga oladi va komponentlarni yaratishdan tortib, foydalanuvchi interaktivligini qo'llab-quvvatlashgacha bo'lgan barcha funksiyalarni amalga oshiradi.