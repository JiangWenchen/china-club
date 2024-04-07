
 # **Хань Фэн Яа Юнь（汉风雅韵）**
 
<img align="right" width="210" height="368" src="cloud/logo.jpg">

## **Содержание**
- [Обзор](#обзор)
  - [О названии](#о-названии)
  - [Цели создания интернет-магазина](#Цели-создания-интернет-магазина)
- [Целевая архитектура](#Целевая-архитектура)
- [Системные требования для открытия интернет-магазина](#системные-требования-для-открытия-интернет-магазина)
  - [Платформа для электронной коммерции](#платформа-для-электронной-коммерции)
  - [Фотосъемка и украшение товара](#фотосъемка-и-украшение-товара)
  - [Логистика и дистрибуция](#логистика-и-дистрибуция)
  - [Обслуживание клиентов](#обслуживание-клиентов)
  - [Маркетинговое продвижение](#маркетинговое-продвижение)
- [Работа интернет-магазина](#работа-интернет-магазина)
  - [Предварительная подготовка](#предварительная-подготовка)
  - [Обслуживание клиентов и послепродажное обслуживание](#обслуживание-клиентов-и-послепродажное-обслуживание)
  - [Анализ и корректировка данных](#анализ-и-корректировка-данных)
  - [Складирование и логистика](#складирование-и-логистика)

## **Обзор**
### **О названии**
Выбор ***"Хань Фэн Яа Юнь"*** в качестве названия этого китайского интернет-магазина не только отражает уважение и любовь к традиционной китайской культуре, но и желание продвигать китайскую культуру в мире через такой интернет-магазин, надеясь предоставить покупателям не только товары, но и культурный опыт и удовольствие. Название не только уникально, но и многозначительно, что позволяет легко привлечь покупателей, интересующихся китайской культурой.  
> Название ***"Хань Фэн"*** олицетворяет традиционную китайскую культуру, представленную "культурой Хань". Использование "Хань Фэн" в названии призвано показать характеристики товаров, продаваемых в магазине, а также дать людям ощущение старомодной элегантности.
> ***"Яа Юнь"*** олицетворяет элегантность и культурный колорит, передавая желание магазина приносить покупателям не только материальное удовлетворение, но и некое духовное наслаждение и культивацию.
### **Цели создания интернет-магазина**
Есть две основные цели открытия интернет-магазина: бизнес-цели и цели, приносящие ценность.
>Бизнес-цели в основном включают в себя следующие пункты:
>1. Наследование и продвижение китайской культуры. Продавая продукцию с традиционным китайским стилем и характеристиками, мы распространяем китайскую культуру во внешний мир и повышаем осведомленность и понимание людьми китайской культуры.
>2. Удовлетворение потребностей потребителей. В магазине представлен широкий выбор товаров в китайском стиле, включая одежду, продукты питания, поделки и т. д.
>3. Повысьте удовлетворенность клиентов. Стремимся обеспечить высокое качество обслуживания клиентов, включая удобный и быстрый процесс совершения покупок, внимательное обслуживание клиентов и послепродажную поддержку.

>Цели создания добавленной стоимости в основном включают в себя следующие пункты:
>1. Создание экономических выгод. Достигайте прибыльности, предоставляя уникальные продукты и услуги для получения экономической выгоды и привлечения большего количества клиентов.
>2. Инновационный дизайн и улучшение процесса. Стремится к инновационному дизайну и совершенствованию процессов, созданию продукции с китайскими характеристиками и высоким качеством, а также содействию развитию и модернизации отрасли.

## **Целевая архитектура**
В этом разделе представлена ​​архитектура интернет-магазина.
### **Схема бизнес-процессов**
В процессе разработки карты бизнес-процессов с применением техники Event Storming для интернет-магазина китайских специализированных товаров целью является определение и визуализация ключевых событий, команд, и акторов, взаимодействующих в процессе выбора, покупки, доставки товара и обслуживания клиентов.
> Цель: Получить четкое представление о процессе онлайн-покупок с момента входа покупателя на сайт до момента получения товара.

> Участники: потребители, аналитики, маркетологи.

> Материалы: Разноцветные стикеры разных форм и большая поверхность для наклеивания
<img width="541" alt="525955bd06eaf6b5c4897d02ebc1c27" src="https://github.com/JiangWenchen/china-club/assets/165254698/70bd7715-1222-4b71-a5a4-afab450d7067">

### **Таблица анализа стейкхолдера**  
Для интернет-магазинов важно проанализировать заинтересованные стороны. Заинтересованные стороны интернет-магазина - это потребители, акционеры, логистические компании, государство, поставщики и другие компании.  

<img width="541" alt="525955bd06eaf6b5c4897d02ebc1c27" src="https://github.com/JiangWenchen/china-club/blob/main/cloud/%E5%88%A9%E7%9B%8A%E7%9B%B8%E5%85%B3%E8%80%85.png">

### **Контекстная диаграмма интернет-магазина**
Следующая диаграмма контекста системы описывает ключевых пользователей системы и их внешние зависимости:

<img width="541" alt="525955bd06eaf6b5c4897d02ebc1c27" src="https://github.com/JiangWenchen/china-club/blob/main/cloud/%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BD%D0%BE%D0%B9%20%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B5.png)">
