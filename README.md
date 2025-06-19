# Wix Custom Preloader Script for India Day Website

A full-screen custom preloader for Wix websites featuring a zoom-in logo animation with colorful particle explosion effects. This preloader overlays the entire viewport — including header, footer, and all page content — and fades out smoothly after the animation completes.

---

## 🎬 Demo

Here is a demo of what the preloader animation looks like:

![Custom Preloader Animation](./preloader.gif)

---

## Features

- Covers the entire viewport (header, footer, and page content)
- Zoom-in animation on your custom logo or image
- Colorful particle explosion effects
- Smooth fade-out after 6 seconds (configurable)
- Responsive design for mobile devices

---

## Prerequisites

- A Wix website with access to the **Wix Editor** and **Wix Dashboard**
- Your preloader image uploaded to Wix Media Manager
- Basic familiarity with Wix Editor and Wix Dashboard

---

## Setup Instructions

### 1. Upload Your Preloader Image to Wix Media Manager

1. Open your Wix site in the **Wix Editor**.  
2. Click **Media** (left panel).  
3. Click **Upload Media** → **Upload from Computer**.  
4. Select your preloader image file (PNG, GIF, etc.).  
5. After upload, click the image → **File Info** → copy the **direct URL**.

### 2. Update the Preloader Code with Your Image URL

1. Open the code snippet file (`preloader.html` or your custom code file).  
2. Find the placeholder `YOUR_IMAGE_URL_HERE`.  
3. Replace it with your copied image URL, for example:

   ```
    <img src="https://static.wixstatic.com/media/your-uploaded-image.png" alt="Preloader Logo" class="logo" />


   ```

### 3. Add the Custom Code to Wix Dashboard

1. Go to your **Wix Dashboard** (not the Editor).  
2. Navigate to **Settings** → **Custom Code**.  
3. Click **+ New Custom Code**.  
4. Paste the entire updated code snippet (HTML, CSS, and JavaScript) into the code box.  
5. Under **Add Code to Pages**, select **All Pages** (or specific pages if preferred).  
6. Under **Place Code In**, select **Head**.  
7. Save and **Publish** your site.

### 4. Test Your Preloader

1. Open your published Wix website in a new browser tab.  
2. The preloader overlay with your custom image should appear, zoom in, and trigger particle explosions.  
3. After approximately 6 seconds, the preloader fades out smoothly, revealing your site content.

---

## Customization

- **Background Color:** Change the `background-color` in the CSS `#preloader` selector.  
- **Animation Timing:** Adjust the durations in the JavaScript `setTimeout` calls.  
- **Particle Colors:** Modify the `colors` array in the JavaScript.  
- **Responsive Settings:** Tweak CSS media queries for different screen sizes.

---

## Troubleshooting

- If the preloader does not appear, verify that the custom code is added to the **Head** section and published.  
- Confirm your image URL is correct and publicly accessible.  
- Wix Preview mode may not fully support custom code; always test on the **live published site**.  
- Clear browser cache if changes do not show immediately.

---

## Русская версия (Russian Version)

# Скрипт кастомного прелоадера для сайта Wix на тему Дня Индии

Полноэкранный кастомный прелоадер для сайтов Wix с анимацией увеличения логотипа и эффектами цветного взрыва частиц. Прелоадер накрывает весь экран, включая шапку, подвал и весь контент страницы, плавно исчезая после завершения анимации.

---

## 🎬 Демонстрация

Ниже показано, как выглядит анимация прелоадера:

![Custom Preloader Animation](./preloader.gif)

---

## Особенности

- Покрывает весь экран (шапка, подвал и контент)  
- Анимация увеличения вашего кастомного логотипа или изображения  
- Цветные эффекты взрыва частиц  
- Плавное исчезновение через 6 секунд (настраивается)  
- Адаптивный дизайн для мобильных устройств

---

## Требования

- Сайт на Wix с доступом к **Wix Editor** и **Wix Dashboard**  
- Ваше изображение прелоадера загружено в Wix Media Manager  
- Базовые знания работы с Wix Editor и Wix Dashboard

---

## Инструкция по установке

### 1. Загрузите изображение прелоадера в Wix Media Manager

1. Откройте ваш сайт в **Wix Editor**.  
2. Нажмите **Media** (левая панель).  
3. Нажмите **Upload Media** → **Upload from Computer**.  
4. Выберите файл изображения прелоадера (PNG, GIF и т.д.).  
5. После загрузки нажмите на изображение → **File Info** → скопируйте **прямой URL**.

### 2. Обновите код прелоадера, вставив URL вашего изображения

1. Откройте файл с кодом (`preloader.html` или ваш кастомный код).  
2. Найдите плейсхолдер `YOUR_IMAGE_URL_HERE`.  
3. Замените его на скопированный URL, например:

   ```
   <img src="https://static.wixstatic.com/media/your-uploaded-image.png" alt="Preloader Logo" class="logo" />

   ```

### 3. Добавьте кастомный код в Wix Dashboard

1. Перейдите в **Wix Dashboard** (не в редактор).  
2. Откройте **Settings** → **Custom Code**.  
3. Нажмите **+ New Custom Code**.  
4. Вставьте весь обновленный код (HTML, CSS, JavaScript) в поле.  
5. В разделе **Add Code to Pages** выберите **All Pages** (или нужные страницы).  
6. В разделе **Place Code In** выберите **Head**.  
7. Сохраните и опубликуйте сайт.

### 4. Проверьте прелоадер

1. Откройте опубликованный сайт в новой вкладке браузера.  
2. Прелоадер с вашим изображением должен появиться, увеличить логотип и запустить взрыв частиц.  
3. Через ~6 секунд прелоадер плавно исчезнет, показывая содержимое сайта.

---

## Настройка

- **Цвет фона:** измените `background-color` в CSS для `#preloader`.  
- **Длительность анимации:** настройте значения в `setTimeout` в JavaScript.  
- **Цвета частиц:** измените массив `colors` в JavaScript.  
- **Адаптивность:** настройте медиа-запросы CSS для разных экранов.

---

## Устранение неполадок

- Если прелоадер не появляется, проверьте, что код добавлен в раздел **Head** и опубликован.  
- Убедитесь, что URL изображения правильный и доступен публично.  
- В режиме предпросмотра Wix кастомный код может работать некорректно — проверяйте на опубликованном сайте.  
- Очистите кеш браузера, если изменения не отображаются.

---