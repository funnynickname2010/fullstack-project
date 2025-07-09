# 🐶 Fullstack Doggo Pinterest

Приложение для просмотра изображений и видео с собаками в стиле Pinterest, созданное на React, TypeScript и Vite.

---

## 📚 Содержание
- [Общая информация](#общая-информация)
- [Технологии](#технологии)
- [Функционал](#функционал)
- [Установка](#установка)

---

<details>
<summary><strong>Общая информация</strong></summary>

Это приложение представляет собой галерею в стиле Pinterest, где пользователи могут:

- Просматривать сетку изображений и видео с собаками  
- Ставить лайки постам (кликом или двойным тапом)  
- Просматривать все понравившиеся посты на отдельной странице  
- Видеть количество лайков у каждого поста  

</details>

<details>
<summary><strong>Технологии</strong></summary>

### Фронтенд  
- React: v18.2.0  
- TypeScript: v5.1.6  
- Vite: v4.3.9  
- Material UI: v5.14.0  
- Tanstack/React Query: v4.29.5  
- React Router: v6.14.0  
- Axios: v1.4.0  

### Бэкенд  
- Express: v5.1.0  
- TypeScript: v5.8.3  
- Axios: v1.10.0  

</details>

<details>
<summary><strong>Функционал</strong></summary>

- 📌 Сетка в стиле Pinterest  
- 🧱 Адаптивная masonry-сетка под разный размер медиа  
- 🖼️ Поддержка изображений и видео  

### 💗 Система лайков  
- Лайк по клику на иконку сердца  
- Лайк по двойному тапу на карточку (удобно для мобильных)  
- Сохранение избранного в `localStorage`  
- Обновление счетчика лайков в реальном времени  

### ⭐ Страница избранного  
- Отдельная страница с понравившимися постами  

### 📄 Пагинация  
- На всех страницах  

</details>

<details>
<summary><strong>Установка</strong></summary>

### Настройка бэкенда
```bash
git clone https://github.com/Anna1719/FullstackTask.git
cd ./server
npm install
npm run dev

### Настройка фронтенда
cd ./client
npm install
npm run dev

Приложение будет доступно по адресу:
👉 http://localhost:5173

### Сборка для продакшена
# фронтенд
npm run build

# бэкенд
npm run build && npm start
</details> ```
