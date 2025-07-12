# 7-дневный план запуска iGaming Organization Hub

## День 1: Установка и базовая настройка
✅ Установка WordPress на хостинг
✅ Установка обязательных плагинов:
   - Custom Post Type UI
   - Advanced Custom Fields Pro
   - WP All Import Pro
   - Elementor Pro
   - RankMath Pro
✅ Импорт базовой структуры из `/wordpress-implementation/phase-2-structure/`

## День 2: Импорт данных
✅ Подготовка CSV из JSON файлов (скрипт в `/data/preparation-scripts/`)
✅ Тестовый импорт 100 позиций
✅ Проверка и корректировка маппинга
✅ Полный импорт 4,127 позиций

## День 3: AI-генерация контента
✅ Настройка Jetpack AI
✅ Импорт промптов из `/ai-content-generation/chatgpt-prompts/`
✅ Bulk-генерация описаний для позиций
✅ Генерация meta-данных через RankMath

## День 4: Установка интерактивных инструментов
✅ Organization Explorer:
   - Копировать код из `/interactive-tools/organization-explorer/`
   - Вставить через Elementor HTML widget
   - Настроить shortcode [igaming_org_chart]
✅ Career Navigator:
   - Установить компоненты визуализации
   - Настроить REST API endpoints
✅ Базовый Business Builder:
   - Установить калькулятор команды
   - Настроить форму конфигуратора

## День 5: SEO-оптимизация
✅ Импорт настроек RankMath из `/seo-optimization/rankmath-configs/`
✅ Настройка Schema markup для всех CPT
✅ Создание XML sitemap с приоритетами
✅ Настройка внутренней перелинковки

## День 6: Автоматизация n8n
✅ Установка n8n (локально или облако)
✅ Импорт workflow из `/n8n-automation/workflows/`
✅ Настройка WordPress REST API
✅ Запуск автоматического обновления контента

## День 7: Тестирование и запуск
✅ Проверка всех страниц и функций
✅ Тестирование скорости загрузки
✅ Отправка sitemap в Google Search Console
✅ Настройка Google Analytics
✅ Soft launch для тестовой группы