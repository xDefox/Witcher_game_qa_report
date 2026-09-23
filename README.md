# The Witcher — QA Portfolio

**Дата тестирования:** 17–21.09.2026  
**Версия игры:** 1.0  
**Платформа:** Windows 11  
**Тип тестирования:** Functional, UI/UX, Performance

Оригинальный проект: [The Witcher](https://github.com/top-secret666/the-witcher)

---

## 📌 Обзор проекта

В этом репозитории собраны результаты QA-проверки игры The Witcher: функциональные блокеры, UI-регрессии и проблемы с производительностью, выявленные в процессе тестирования.

## 📋 Баг-репорты

| ID | Тип | Заголовок | Severity | Priority | Ссылка |
|---|---|---|---|---|---|
| FUNC-001 | Functional/UI | Отклик на Esc | Major | Medium | [Открыть](BugReports/FUNC_001_Esc_Menu.md) |
| FUNC-004 | Functional/UI | Ошибка управления стрелками в меню паузы | Major | Medium | [Открыть](BugReports/FUNC_004_Menu_Overlay_Error.md) |
| FUNC-005 | Functional/UI | Блокировка снимков экрана | Minor | Low | [Открыть](BugReports/FUNC_005_Screenshot_Block.md) |
| FUNC-007 | Functional/UI | Невозможно пропустить анимацию появления предметов в лавке | Major | Medium | [Открыть](BugReports/FUNC_007_Cant_Skip_Animation.md) |
| FUNC-009 | Functional | Полное зависание игры при старте «Новой игры +» | Minor | Low | [Открыть](BugReports/FUNC_009_NewGame+_Crash.md) |
| PERF-010 | Performance | Низкий FPS в диалогах и геймплее | Minor | Low | [Открыть](BugReports/PERF_010_FPS_Drop.md) |
| UI-002 | UI | Нежданный отклик интерфейса в инвентаре | Major | Medium | [Открыть](BugReports/UI_002_Inventory_Visual_Bug.md) |
| UI-003 | UI | Нарушена степень пикселизации в сцене 1 | Major | High | [Открыть](BugReports/UI_003_Pixel_Text_View.md) |
| UI-006 | UI | Пиксельное отображение мечей в инвентаре | Major | Medium | [Открыть](BugReports/UI_006_Knife_Visual_After_Buying.md) |
| UI-008 | UI | Плавающая кнопка паузы | Major | Medium | [Открыть](BugReports/UI_008_Unsecured_Pause_Button.md) |

---

## 📊 Performance Testing

- [CSV-лог с метриками](performance-Tests/Hardware.20260921-183828.CSV)

---

## 💡 Предложения по улучшению

- Унифицировать шрифт, размер и степень пикселизации во всех сценах игры.
- Зафиксировать кнопку паузы в одном положении на всех сценах.
- Увеличить чувствительность ползунка скорости текста.
- Разделить интерфейсы магазина и инвентаря.
- Проверить и оптимизировать производительность в диалоговых сценах.