# System Specification Document (SSD)

## 1. Purpose
Система моніторингу призначена для збору логів, метрик та подій з розподіленої інфраструктури. Вона забезпечує централізований контроль стану системи.

## 2. Functional Requirements

- FR-01: Збір логів з мікросервісів
- FR-02: Обробка метрик у реальному часі
- FR-03: Виявлення аномалій
- FR-04: Генерація алертів

## 3. Constraints

- Тільки API-based взаємодія
- Підтримка горизонтального масштабування

## 4. Non-functional Requirements

- Performance: до 200 ms
- Availability: 99.9%
- Security: JWT authentication + TLS 1.3
