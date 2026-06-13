FishGo Marine project

Структура:
- index.html — главная страница
- seafood.html — каталог морепродуктов
- accessories.html — рыболовные аксессуары
- about.html — о компании и контакты
- css/style.css — стили сайта
- js/main.js — слайдеры, карточки, мобильное меню, уведомления
- assets/images — папка для фото
- assets/video — папка для видео

Как добавить фото:
1. Закиньте изображения в assets/images
2. В HTML или JS замените текстовые блоки «место под фото» на тег:
   <img src="assets/images/name.jpg" alt="Описание">

Как добавить видео на главную:
1. Закиньте файл в assets/video
2. В index.html внутри блока .media-slot можно заменить плейсхолдер на:
   <video src="assets/video/fishing.mp4" autoplay muted loop playsinline></video>

Анимация загрузки длится около 1 секунды, не больше 5–10 секунд.
