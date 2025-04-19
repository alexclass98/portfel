# 📈 Investment Portfolio Tracker

**Инструмент для отслеживания и анализа вашего инвестиционного портфеля с возможностью интеграции с Тинькофф Инвестиции.**

[![Language Python](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)
[![Framework Django](https://img.shields.io/badge/Framework-Django-0C3C26.svg?logo=django)](https://www.djangoproject.com/)
[![Language TypeScript](https://img.shields.io/badge/Language-TypeScript-blue.svg?logo=typescript)](https://www.typescriptlang.org/)
[![Library React](https://img.shields.io/badge/Library-React-61DAFB.svg?logo=react)](https://reactjs.org/)
[![License MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

![image](https://github.com/user-attachments/assets/fc1a8114-aa87-41c8-bafc-3246f53aed00)


## 🌟 Основные Возможности

*   **Управление Портфелями:** Создание, просмотр, редактирование и удаление нескольких инвестиционных портфелей.
*   **Отслеживание Активов:** Добавление различных типов активов (акции, облигации, ETF) в портфель, отслеживание их количества, средней цены покупки и текущей стоимости.
*   **Учет Сделок:** Запись операций покупки и продажи активов с указанием даты, количества, цены и комиссий.
*   **Аналитика:** Расчет общей стоимости портфеля, прибыли/убытка (P/L), доходности в процентах. (Опционально: Визуализация с помощью графиков).
*   **Интеграция с Тинькофф Инвестиции:** 🚀 Импорт данных о состоянии портфеля напрямую из вашего брокерского счета Тинькофф с использованием Tinkoff Invest API v2.
*   **Генерация Демо-Данных:** Скрипт для быстрого заполнения базы данных тестовыми данными для демонстрации.
*   **Аутентификация Пользователей:** Безопасный вход и регистрация (реализовано через Django).

## 🛠️ Технологический Стек

*   **Бэкенд:**
    *   Python 3.10+
    *   Django 4+
    *   Django REST Framework (DRF)
    *   Tinkoff Invest SDK (`tinkoff-investments`)
    *   PostgreSQL (рекомендуется) / SQLite (для разработки)
*   **Фронтенд:**
    *   TypeScript
    *   React 18+
    *   Redux Toolkit (или другой state manager)
    *   Material UI (или другая UI библиотека)
    *   Axios (для HTTP запросов)
    *   (Опционально: Recharts/Chart.js для графиков)
*   **Инструменты:**
    *   Node.js & npm/yarn
    *   Git & GitHub
