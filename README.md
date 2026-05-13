

# Tereveni

> Modern social media platform for communication, discussions and real-time interaction.

[![Vercel](https://img.shields.io/badge/Live%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://terevenimo.vercel.app/)
[![Backend](https://img.shields.io/badge/Backend-GitHub-181717?style=flat-square&logo=github)](https://github.com/SehiiKolesnykov/final_project_back_2025)

---

# About the Project

Tereveni is a social networking platform inspired by X (Twitter).

The application allows users to share posts, participate in discussions, communicate in private chats, follow other users, and interact through likes, bookmarks, comments and real-time notifications.

The project was created as a large educational team project focused on frontend architecture, real-time communication, state management, API integration and collaborative development.

---

# Features

## Authentication

- Registration and login with email/password
- Google OAuth authentication
- JWT-based authorization
- Automatic token refresh
- Protected routes

---

## Posts

- Create posts with text and images
- Edit and delete personal posts
- Upload images with Cloudinary
- Infinite feed scroll
- Sort posts:
  - newest
  - most popular
  - most commented

---

## Social Interaction

- Post comments
- Likes system
- Save posts to favorites
- Follow/unfollow users
- Real-time notifications using WebSocket
- Real-time private chat using WebSocket

---

## Search & Filtering

- Search posts by content
- Search users by first and last name
- Real-time filtering

---

## UX/UI

- Responsive design
- Dark theme
- Confirmation modals
- Reusable UI components
- Optimistic UI updates

---

# Tech Stack

## Frontend

```bash
├── React 18 + Vite           # Frontend framework and bundler
├── Redux Toolkit             # Global state management
├── React Router v6           # Routing
├── Styled Components         # CSS-in-JS styling
├── WebSocket + STOMP         # Real-time communication
├── Cloudinary SDK            # Image uploading
└── PropTypes                 # Props validation
````

## Backend

```bash
├── Spring Boot (Java)        # REST API
├── PostgreSQL                # Database
├── JWT                       # Authentication
└── Cloudinary                # Media storage
```

---

# Backend Repository

Backend API repository:

https://github.com/SehiiKolesnykov/final_project_back_2025

---

# Installation & Setup

## Requirements

* Node.js 18+
* npm

---

## Clone Repository

```bash
git clone https://github.com/yarvil/widi.git
```

---

## Install Dependencies

```bash
npm install
```

---

## Start Development Server

```bash
npm run dev
```

Application will be available at:

```bash
http://localhost:5173
```

---

## Production Build

```bash
npm run build
npm run preview
```

---

# Project Structure

```bash
src/
├── api/                          # API requests and client configuration
│   ├── auth.js
│   ├── posts.js
│   ├── comments.js
│   ├── users.js
│   ├── messages.js
│   ├── notifications.js
│   └── client.js
│
├── app/                          # Application configuration
│   ├── store/                    # Redux Toolkit store
│   │   ├── authentication/
│   │   ├── posts/
│   │   ├── users/
│   │   ├── chat/
│   │   ├── notifications/
│   │   └── follows/
│   │
│   ├── router/                   # React Router configuration
│   └── styles/                   # Global styles
│
├── hooks/                        # Custom React hooks
│   ├── usePostActions.js
│   ├── useUser.js
│   ├── useChatWebSocket.js
│   └── useNotificationsSocket.js
│
├── pages/                        # Application pages
│   ├── auth/
│   ├── feed/
│   ├── post/
│   ├── profile/
│   ├── chat/
│   ├── follow/
│   ├── notifications/
│   └── favoriteList/
│
├── shared/                       # Shared reusable modules
│   ├── ui/                       # UI components
│   ├── components/               # Business components
│   ├── assets/                   # Icons and images
│   └── utils/                    # Helper functions
│
└── main.jsx                      # Application entry point
```

---

# Technical Highlights

## Redux Architecture

* Redux Toolkit with `createSlice`
* Async logic using `createAsyncThunk`
* Backend data normalization
* Optimistic UI updates
* Infinite scroll pagination

---

## WebSocket Integration

### Real-Time Chat

* Private messaging between users
* STOMP protocol support
* Automatic reconnect handling

### Notifications

* Instant updates for:

  * likes
  * comments
  * follows

---

## Components & Styling

* Styled Components architecture
* Reusable UI system
* Responsive layout
* PropTypes validation

---

## Performance & Optimization

* Lazy-loaded routes
* Search debounce
* Optimistic rendering
* API request separation

---

# My Contributions

As part of the frontend team, I contributed to:

* Real-time chat functionality
* Redux Toolkit state management
* UI components
* REST API integration
* Authentication-related features
* Team collaboration and frontend architecture discussions

---

# Deployment

## Frontend

https://terevenimo.vercel.app/

## Backend

https://github.com/SehiiKolesnykov/final_project_back_2025

---

# Development Team

## Frontend Developers

* [@yarvil](https://github.com/yarvil)
* [@Kosta45](https://github.com/Kosta45)
* [@Mykola-Pyshnyuk](https://github.com/Mykola-Pyshnyuk)
* [@ruslanivanovich](https://github.com/ruslanivanovich)
* [@arcanit33](https://github.com/arcanit33)

## Backend Developers

* [@SehiiKolesnykov](https://github.com/SehiiKolesnykov)
* [@OleksiiZharkov](https://github.com/OleksiiZharkov)
* [@Olenka19965](https://github.com/Olenka19965)
* [@AndreychykViktor](https://github.com/AndreychykViktor)

---

# Notes

This project was created as a learning team project and became valuable practical experience in:

* frontend development
* team collaboration
* state management
* API integration
* WebSocket communication
* large-scale React application structure

Some parts of the application can still be improved and expanded in the future, but the project already demonstrates real-world frontend development concepts and collaborative workflow experience.

---

```
```



# Ukrainian Version (Original)

# Теревені (Tereveni)

> Сучасна соціальна мережа для спілкування, обміну думок та дискусій

[![Vercel](https://img.shields.io/badge/Live%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://terevenimo.vercel.app/)
[![Backend](https://img.shields.io/badge/Backend-GitHub-181717?style=flat-square&logo=github)](https://github.com/SehiiKolesnykov/final_project_back_2025)

---

## Про проект

Теревені — це соціальна мережа, створена як альтернатива X (Twitter). Платформа дозволяє користувачам ділитися думками, коментувати пости, підписуватися на інших користувачів, вести особисті переписки та взаємодіяти через систему лайків і збережень.

---

## Функціонал

#### Автентифікація

- Реєстрація та вхід через email/пароль
- Авторизація через Google OAuth
- JWT токени для безпечних сесій
- Автоматичне оновлення токенів

#### Робота з постами

- Створення постів з текстом та зображеннями
- Редагування власних постів
- Видалення постів
- Завантаження зображень через Cloudinary
- Сортування постів (найновіші, найпопулярніші, за кількістю коментарів)

#### Взаємодія

- Коментарі до постів
- Лайки
- Збереження постів в обране
- Підписки на користувачів
- Система сповіщень у реальному часі (WebSocket)
- Чат між користувачами (WebSocket)

#### Пошук

- Пошук постів за вмістом
- Пошук користувачів за ім'ям та прізвищем
- Фільтрація в реальному часі

#### UX/UI

- Адаптивний дизайн
- Безкінечний скрол постів (infinite scroll)
- Модальні вікна для підтвердження дій
- Темна тема

---

## Технологічний стек

### Frontend

```
├── React 18 + Vite           # Швидкий dev server та build
├── Redux Toolkit             # Управління стейтом
├── React Router v6           # Маршрутизація
├── Styled Components         # CSS-in-JS стилізація
├── WebSocket                 # Реальний час (чат, сповіщення)
├── Cloudinary SDK            # Завантаження зображень
└── PropTypes                 # Валідація пропсів
```

### Backend

```
├── Spring Boot (Java)        # RESTful API
├── PostgreSQL                # База даних
├── JWT                       # Аутентифікація
└── Cloudinary                # Зберігання зображень
```

**[ Повна документація Backend API](https://github.com/SehiiKolesnykov/final_project_back_2025)**

---

## Встановлення та запуск

### Передумови

- Node.js 18+ та npm

### 1. Клонування репозиторію

```bash
# Frontend
git clone https://github.com/yarvil/widi.git
```

### 2. Налаштування Frontend

```bash
# Встановлення залежностей
npm install

# Створення .env файлу (опціонально)
# VITE_API_URL=http://localhost:5173

# Запуск dev сервера
npm run dev
```

Додаток буде доступний на `http://localhost:5173`

### 4. Build для продакшену

```bash
npm run build
npm run preview  # Перегляд production білда
```

---

## Структура проєкту

```
src/
├── api/                          # API клієнт та запити
│   ├── auth.js                   # Автентифікація
│   ├── posts.js                  # Пости
│   ├── comments.js               # Коментарі
│   ├── users.js                  # Користувачі
│   ├── messages.js               # Чат
│   ├── notifications.js          # Сповіщення
│   └── client.js                 # Базовий клієнт
├── app/                          # Конфігурація додатку
│   ├── store/                    # Redux store
│   │   ├── authentication/
│   │   ├── posts/
│   │   ├── users/
│   │   ├── chat/
│   │   ├── notifications/
│   │   └── follows/
│   ├── router/                   # React Router конфігурація
│   └── styles/                   # Глобальні стилі
├── hooks/                        # Кастомні React хуки
│   ├── usePostActions.js
│   ├── useUser.js
│   ├── useChatWebSocket.js            # WebSocket для чату
│   └── useNotificationsSocket.js      # WebSocket для сповіщень
├── pages/                        # Сторінки додатку
│   ├── auth/                     # Реєстрація/логін
│   ├── feed/                     # Головна стрічка
│   ├── post/                     # Детальна сторінка поста
│   ├── profile/                  # Профіль користувача
│   ├── chat/                     # Месенджер
│   ├── follow/                   # Підписки
│   ├── Notifications/            # Сповіщення
│   └── FavoriteList/             # Збережені пости
├── shared/                       # Переиспользуємі компоненти
│   ├── ui/                       # UI компоненти (кнопки, модалки, хедер)
│   ├── components/               # Бізнес-компоненти (PostCard, UserCard)
│   ├── assets/                   # Іконки, логотипи
│   └── utils/                    # Допоміжні функції
└── main.jsx                      # Точка входу
```

---

## Основні можливості коду

### Redux архітектура

- **Redux Toolkit** з `createSlice` та `createAsyncThunk`
- Нормалізація даних з бекенду
- Оптимістичні UI оновлення для лайків та збережень
- Пагінація з infinite scroll

### WebSocket інтеграція

- **Чат**: Приватні повідомлення у реальному часі через STOMP
- **Сповіщення**: Миттєві оновлення про лайки, коментарі, підписки
- Автоматичне перепідключення при розриві з'єднання

### Компоненти

- Styled Components
- Адаптивний дизайн
- Перевикористовувані UI компоненти
- PropTypes

### Оптимізації

- Lazy loading маршрутів
- Debounce для пошуку
- Оптимістичні оновлення UI

---

## Деплой

**Frontend:** [Vercel](https://terevenimo.vercel.app/)  
**Backend:** [Backend репозиторій](https://github.com/SehiiKolesnykov/final_project_back_2025)

---

## Команда розробників

| Роль               | GitHub                                                   |
| ------------------ | -------------------------------------------------------- |
| Frontend Developer | [@yarvil](https://github.com/yarvil)                     |
| Frontend Developer | [@Kosta45](https://github.com/Kosta45)                   |
| Frontend Developer | [@Mykola-Pyshnyuk](https://github.com/Mykola-Pyshnyuk)   |
| Frontend Developer | [@ruslanivanovich](https://github.com/ruslanivanovich)   |
| Frontend Developer | [@arcanit33](https://github.com/arcanit33)               |
| Backend Developer  | [@SehiiKolesnykov](https://github.com/SehiiKolesnykov)   |
| Backend Developer  | [@OleksiiZharkov](https://github.com/OleksiiZharkov)     |
| Backend Developer  | [@Olenka19965](https://github.com/Olenka19965)           |
| Backend Developer  | [@AndreychykViktor](https://github.com/AndreychykViktor) |

---

## Примітки

Проєкт створено з навчальною метою. Деякі функції можуть бути спрощені порівняно з повноцінно працюючими додатками, велику частину функціоналу не реалізовано через брак часу та складною ситуацією зі світлом. Ми обговоримо з командою щодо подальшої підтримки проєкту але вже в зручному темпі для подальшого використання його як pet проєкт для своїх портфоліо.

Це наш перший проєкт, який був створений у великій (для нас велика) команді, тому присутні помилки та дублювання у коді, трохи хаосу в комітах, та загальна структура проєкту потребує ретельного перегляду. Без реальної практики цих проблем неможливо уникнути і певний досвід ми отримали.
