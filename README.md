<div align="center">

# 🛠️ Development Portfolio

[![Live CV](https://img.shields.io/badge/Відкрити-CV-35439F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://ephtianura.github.io/CV/)
[![Source Code](https://img.shields.io/badge/Source_Code-CV-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ephtianura/CV)

</div>

> **Про цей репозиторій:** Тут зібрані мої основні проєкти, які найкраще демонструють підхід до розробки, архітектурні рішення та використані технології.

## 🧭 Навігація за каталогом

| Проєкт                            | Домен                 | Стек                             | Результат                                                                       |
| :-------------------------------- | :-------------------- | :------------------------------- | :------------------------------------------------------------------------------ |
| **[🌸 AniFlow](#aniflow)**        | Web / Highload        | .NET 8, Next.js, RabbitMQ, Redis | Повний цикл розробки та впровадження продукту                                   |
| **[🌌 Aurora](#aurora)**          | Web / Desktop / Media | .NET 8, React, FFmpeg, SignalR   | Пакетна конвертація, унікальна логіка                                           |
| **[⚙️ Grinding Calculator](#grinding)** | Engineering           | C#, .NET, WinForms               | Рутина інженерів **120 хв $\rightarrow$ 5 хв**, впроваджено в навчальний процес |
| **[🛡️ Posture Guard](#posture)**  | Hardware / IoT        | C++, ESP8266, Схемотехніка       | Від схеми до міжнародних нагород                                                |

<h2 id="aniflow">🌸 AniFlow – Агрегатор Українського Аніме Контенту</h2>

<div align="center">
  <img src="https://github.com/user-attachments/assets/579bbc32-8462-477f-af13-26ddaa5c43b4" alt="aniflow-banner" width="90%"/>

[![Live](https://img.shields.io/badge/Live-aniflow.xyz-AB5BDB?style=for-the-badge&logo=slint&logoColor=white)](https://aniflow.xyz)
[![Repository](https://img.shields.io/badge/Repository-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ephtianura/AniFlow)

<!-- 181717 24292F 010409 -->
</div>

**AniFlow** – працюючий на ринку повнофункціональний сервіс для перегляду аніме українською мовою. 

Автономна платформа з багаторівневим кешуванням, автоматичною синхронізацією каталогу через партнерів, соціальними функціями, вбудованим інструментарієм для моніторингу бізнес-метрик та надійно розгорнутою хмарною інфраструктурою.

_**Стек:** C#, ASP.NET Core, EF Core, PostgreSQL, Redis, RabbitMQ, SignalR, Seq, Nginx, AWS S3, Cloudflare, CI/CD; React, TypeScript, Next.js, TailwindCSS._

<h2 id="aurora">🌌 Aurora – Desktop Комбайн для конвертації музики на вебстеку</h2>

<div align="center">

<img src="./docs/aurora-banner.webp" alt="Aurora Demo" width="90%"/>

[![Repository](https://img.shields.io/badge/Repository-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ephtianura/Aurora)

</div>

Додаток для пакетного завантаження аудіо з YouTube, який самостійно через FFmpeg вкладає обложки, додає метаданні та зберігає готові MP3 прямо в потрібну папку на ПК. Без обмежень і з повноцінним інтерфейсом медіатеки у вигляді зручного проводника.

***Стек:** C#, ASP.NET Core, RabbitMQ, SignalR, FFmpegCore, YouTubeExplode, yt_dlp Docker; React, Next.js, TailwindCSS.*

<h2 id="grinding">⚙️ Grinding Calculator – Інженерне ПЗ автоматизації розрахунку режимів шліфування</h2>

<div align="center">
  <img src="./docs/grinding-banner.png" alt="Grinding Calculator Demo" width="90%"/>

[![](https://img.shields.io/badge/Releases-35439F?style=for-the-badge)](https://github.com/Ephtianura/GrindingCalc/releases/tag/v1.1)
[![Repository](https://img.shields.io/badge/Repository-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ephtianura/GrindingCalc)

</div>

> _«Скоротив час складання технологічної карти з **~120 хвилин до ~5 хвилин**.»_

Прикладне інженерне ПЗ для автоматизації високоточних розрахунків режимів шліфування матеріалів на станках. Застосунок переводить складний масив нормативно-довідкових таблиць та понад 30 наукових формул теорії різання у швидкий покроковий алгоритм. Автоматично валідує вхідні параметри, перевіряє можливість різання та генерує підсумкові карти з можливістю експорту в MS Excel.

Після розробки додаток почали застосовувати у навчальних процесах профільних дисциплін.

***Стек:** C#, .NET, WinForms.*

<h2 id="posture">🛡️ Posture Guard – IoT Система Моніторингу Осанки</h2>

<div align="center">
  <img src="./docs/posture-guard-banner.webp" alt="Posture Guard Demo" width="90%"/>
  
[![](https://img.shields.io/badge/Повна-Презентація-8A2F6F?style=for-the-badge)](https://gamma.app/docs/-e7krxml48le5qmm)
[![Repository](https://img.shields.io/badge/Repository-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ephtianura/PostureGuard)

</div>

**Posture Guard** – автономна IoT-система превентивного моніторингу постави в реальному часі. Передбачає статичне перенапруження хребта при тривалій роботі.

З високою точністю відстежувє кути нахилу хребта в 3-х точках за допомогою акселерометрів, передає дані по протоколу ESP-NOW та повідомляє про порушення пози через світлозвукове сповіщення.

Проєкт відзначений грамотами та офіційними сертифікатами на міжнародних науково-практичних конференціях


***Стек:** С++, Platformio; ESP8266, BMI160, TP4056.*

<h2 id="ai-map">🗺️ AI Map [WIP]</h2>

Desktop додаток, який за допомогою комп'ютерного зору визначає дистанцію та азимут до об'єктів на карті в реальному часі з функцією відстеження.

Проєкт призупинено після завершення активної розробки. Оформлення репозиторію перебуває на стадії доопрацювання.

***Стек:** Python, Ultralytics YOLOv8, OpenCV, PyQt6, MSS*

---

<div align="center">

### 🤝 Готові зв'язатися?

<a href="https://t.me/KykKyki">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" height="36" />
</a>
<a href="https://www.linkedin.com/in/mantsurov-kostiantyn/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="36" />
</a>
<a href="mailto:k.mantsurov@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" height="36" />
</a>
  
</div>
