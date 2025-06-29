# BrokenERP
Доведение до внедрения зашедшего в тупик проекта ERP

# ERP Implementation & Crisis Project Management

## Описание проекта

Этот проект представляет собой успешный кейс по **антикризисному управлению внедрением ERP-системы** на стадии глубокой стагнации. Я был приглашён Заказчиком для проведения **независимого аудита текущего состояния проекта**, оценки его перспектив, рисков, бюджета и сроков реализации. В рамках моего участия проект был выведен из кризисной фазы, реструктурирован и доведён до успешного запуска.

## Роль в проекте

**Product Owner / Антикризисный руководитель проекта**

Мои ключевые задачи:
- Проведение комплексного аудита проекта.
- Формирование новой дорожной карты внедрения.
- Управление изменениями на стороне Заказчика и Исполнителя.
- Контроль качества, сроков, бюджета.
- Управление ожиданиями стейкхолдеров.
- Курирование проблемных модулей (особенно — управление товарными запасами).

## Исходная ситуация

Аудит проекта выявил ряд критических нарушений:
- Исполнитель не выполнил значительный объём работ по этапам анализа и проектирования.
- Этап обследования бизнес-процессов остался неформализованным: документы не были согласованы и содержали существенные ошибки.
- Техническое задание (ТЗ) не утверждено, процесс разработки фактически остановился.
- Модуль "Управление товарными запасами" не соответствовал ни договору, ни предпродажным обещаниям.

## Цели реанимации проекта

- **Оценка реализуемости** текущего плана проекта.
- **Реструктуризация проекта** с новым подходом к планированию и исполнению.
- **Запуск эффективной коммуникации** между всеми участниками.
- **Переопределение приоритетов**, включая переработку модулей с высоким риском (в частности, логистика и запасы).
- **Успешный запуск ERP-системы** в боевом режиме.

---

## Методология

### Комбинированный подход: Waterfall + Scrum

| Методология | Применение |
|-------------|------------|
| **Waterfall** | Для формализации документов, этапов обследования, ТЗ, утверждения архитектуры |
| **Scrum** | Для гибкой разработки и доработки модулей, в т.ч. управления запасами |

### Этапы и фазы

#### 📋 Аудит проекта (2 недели)
- Анализ исходных документов (договора, КП, ТЗ, отчетов по обследованию).
- Интервью с ключевыми стейкхолдерами.
- Оценка степени технической реализации.
- Сравнение факта с планом и предпродажными материалами.
- Подготовка отчета с рисками, предложением по рестарту проекта.

#### 📌 Переопределение стратегии (1 неделя)
- Принятие решения о продолжении проекта с обновленным планом.
- Формирование новой команды на стороне Заказчика (внутренние владельцы процессов).
- Обновление структуры ролей и ответственности.
- Разработка новой дорожной карты с бэклогом.

#### ⚙️ Обновление обследования и ТЗ (3 недели)
- Повторное обследование ключевых бизнес-процессов.
- Внедрение инструментов визуализации (BPMN 2.0, диаграммы потоков).
- Создание и согласование актуального ТЗ.

#### 🧩 Разработка и внедрение модулей (8 спринтов по 2 недели)
- Создание Scrum-команды совместно с Исполнителем.
- Прозрачное планирование спринтов, ежедневные стендапы.
- Внедрение CI/CD-практик (для разработчика).
- Регулярные демо для бизнес-пользователей.
- Интеграционное и пользовательское тестирование.

---

## Фокус: Модуль "Управление товарными запасами"

Особое внимание было уделено модулю, вызвавшему наибольшее недовольство Заказчика:
- Проанализированы расхождения между коммерческим предложением, договором и реализованной функциональностью.
- Проведены интервью с операционными сотрудниками, выявлены реальные сценарии использования.
- Сформирован backlog на доработку.
- Обеспечено гибкое внедрение новой логики расчёта оптимальных запасов, автоматизации заказов и визуализации товарных остатков.

📈 В результате модуль был не просто доработан, а **значительно превосходил ожидания Заказчика**:
- Улучшено планирование закупок.
- Уменьшены запасы на 15% без дефицита.
- Повышена точность прогноза потребности на 25%.

---

## 📅 Диаграмма Ганта

![Диаграмма Ганта проекта ERP](https://github.com/Vladimir-malyshev/BrokenERP/blob/main/gant.png)

---

## Результаты

- ✅ Успешный запуск ERP-системы в ключевых подразделениях.
- ⏱ Проект был завершен в пределах согласованных сроков (с учётом рестарта).
- 💬 Удовлетворённость Заказчика — высокая, зафиксирована в итоговом отчёте.
- 📚 Создана методология повторного запуска ERP-внедрений с нуля.
- 📊 Внедрены инструменты аналитики и контроля эффективности работы ERP.

---

## Технологии и инструменты

- **Методологии:** Waterfall, Scrum
- **Документооборот:** Confluence, Miro, BPMN
- **Управление задачами:** Jira
- **Тестирование:** TestRail, UAT-сценарии

---

## Выводы и рекомендации

- Проект ERP-внедрения может быть успешно спасён при наличии сильного владельца продукта и системного антикризисного подхода.
- Комбинация Waterfall (для документации) и Scrum (для гибкой реализации) обеспечивает оптимальный баланс структурности и гибкости.
- Ключ к успеху — **вовлечённость бизнеса** и **жесткий контроль качества исполнения**.

