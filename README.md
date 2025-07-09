# 🐶 Doggo Pinterest Backend

REST API для галереи изображений и видео с собаками в стиле Pinterest. Серверная часть приложения реализована на Express и TypeScript/JavaScript.  

---

## 📚 Содержание
- [Общая информация](#общая-информация)
- [Технологии](#технологии)
- [Функционал](#функционал)
- [Установка](#установка)

---

<details>
<summary><strong>Общая информация</strong></summary>

Этот backend представляет собой REST API для Pinterest-подобной галереи, который:

- Загружает список файлов с `https://random.dog/doggos`
- Формирует объекты постов с URL, типом файла (видео/изображение) и лайками
- Предоставляет эндпоинты для получения всех постов, конкретного поста и лайка

</details>

<details>
<summary><strong>Технологии</strong></summary>

- Node.js  
- Express: v5.1.0  
- Axios: v1.10.0  
- JavaScript (ESModules)  

</details>

<details>
<summary><strong>Функционал</strong></summary>

### 📦 Эндпоинты API

- `GET /` – получить все посты (если не были загружены ранее — загружаются автоматически)  
- `GET /posts/:filename` – получить конкретный пост по имени файла  
- `POST /like/:filename` – лайкнуть пост (увеличивает счётчик лайков)

### 💾 Обработка данных

- Все посты хранятся в `global.posts` (псевдо-база данных в оперативной памяти)
- Тип медиа определяется по расширению `.mp4`/`.webm` (видео) или другим (изображение)
- Лайки сохраняются в памяти, сбрасываются при перезапуске сервера

</details>

<details>
<summary><strong>Установка</strong></summary>

### 🔧 Запуск проекта

bash
git clone https://github.com/Anna1719/FullstackTask.git
cd server
cd src
npm install
node index.js
Сервер будет доступен по адресу:
👉 http://localhost:3000

</details>

✨ Выполнили: Баринова Анна (front) и Ремез Вячеслав (back)
