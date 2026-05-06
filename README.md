# Digital Bank Credit Decision Platform

## Описание проекта

Digital Bank Credit Decision Platform — проект, в рамках которого проектируется система автоматизации обработки заявок на кредитные карты для условного цифрового банка NovaBank.

Проект покрывает end-to-end процесс: от подачи заявки клиентом до валидации данных, KYC-проверки, скоринга, антифрод-проверки, принятия кредитного решения, формирования оффера и отслеживания статусов заявки.

## Контекст компании

NovaBank — условный цифровой банк, который развивает онлайн-продажи банковских продуктов и хочет сократить долю ручной обработки заявок на кредитные карты.

## Продукт

Онлайн-платформа обработки заявок на кредитные карты.

## Бизнес-проблема

Часть заявок на кредитные карты обрабатывается вручную. Из-за этого увеличивается время принятия решения, растёт операционная нагрузка на сотрудников, повышается риск ошибок и снижается конверсия клиентов.

## Цель проекта

Спроектировать систему, которая автоматизирует обработку кредитных заявок: валидацию данных, KYC-проверку, скоринг, антифрод-проверку, принятие решения, формирование оффера и хранение истории изменения статусов.

## Основной процесс

Клиент подаёт заявку → система валидирует данные → запускает KYC-проверку → запускает скоринг → запускает антифрод-проверку → принимает кредитное решение → формирует оффер → уведомляет клиента.

## Артефакты проекта

- Обзор проекта
- Анализ стейкхолдеров
- Scope / Out of Scope
- AS-IS / TO-BE процесс
- BPMN-диаграмма процесса
- Бизнес-правила
- Таблица решений
- Модель статусов заявки
- Функциональные требования
- Нефункциональные требования
- Use Cases
- Sequence Diagram
- ERD
- SQL-запросы
- REST API specification
- JSON-примеры
- Acceptance Criteria
- Test Cases
- Risk Register
- Analyst Decision Log
- Case Study

## Демонстрируемые навыки

- Бизнес-анализ
- Системный анализ
- Сбор и описание требований
- BPMN
- UML
- ERD
- SQL
- REST API
- JSON
- OpenAPI
- Acceptance Criteria
- Test Cases
- Анализ рисков

## Структура репозитория

```text
digital-bank-credit-decision-platform/
  README.md

  01_Project_Overview/
    Project_Overview.md

  02_Business_Context/
    Stakeholders.md
    Scope.md
    AS_IS_TO_BE.md

  03_Business_Process/
    Business_Rules.md

  04_Requirements/
    Functional_Requirements.md
    Non_Functional_Requirements.md
    Use_Cases.md

  05_System_Analysis/
    JSON_Examples.md
    API_Specification.yaml

  06_Data_Analytics/
    SQL_Queries.sql
    Metrics.md

  08_Project_Management/
    Risks_and_Open_Questions.md
    Analyst_Decision_Log.md

  09_Case_Study/
    Case_Study.md
