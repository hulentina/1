# 1

```maemaid
gantt
    title Интеграция Алисы с Яндекс Маркетом (6 мес)
    dateFormat  YYYY-MM-DD
    axisFormat  %b/%Y

    section Инициация и планирование
    Kick-off & детальная проработка требований       :milestone, m1, 2025-05-01, 2w
    Уточнение требований и дизайн                     :design, 2025-05-15, 4w

    section Разработка
    Архитектурный дизайн & API-спецификация           :api, after design, 6w
    Backend-интеграция Алисы ↔ Маркет                 :dev, after api, 8w

    section UI/UX
    Прототипирование пользовательского интерфейса     :ux, after design, 4w

    section Тестирование
    Интеграционное тестирование                       :intTest, after dev, 4w
    Приемочное тестирование (UAT)                      :uat, after intTest, 2w

    section Деплой и поддержка
    Деплой и Go-live                                  :deploy, after uat, 2w

```
