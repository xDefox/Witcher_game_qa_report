# The Witcher — QA Portfolio

**Дата тестирования:** 17-21.09.2026  
**Версия приложения:** 1.0  
**Платформа:** Windows 11  
**Тип тестирования:** Functional, UI/UX, Performance

---

## 📋 Все баги

| ID | Тип | Заголовок | Severity | Priority | Ссылка |
|---|---|---|---|---|---|
| UI-001 | UI | Отклик на Esc | Major | Medium | [Открыть](BugReports/UI-001_Esc_Menu.md) |
| UI-002 | UI | Подсветка ячейки в инвентаре | Minor | Trivial | [Открыть](BugReports/UI-002_Inventory_Highlight.md) |
| UI-003 | UI | Пикселизация текста | Major | High | [Открыть](BugReports/UI-003_Pixelation.md) |
| UI-004 | UI | Навигация стрелками в меню | Major | Medium | [Открыть](BugReports/UI-004_Arrow_Navigation.md) |
| UI-005 | UI | Блокировка Win+Shift+S | Minor | Low | [Открыть](BugReports/UI-005_Screenshot_Block.md) |
| UI-006 | UI | Низкое разрешение текстуры меча | Major | Medium | [Открыть](BugReports/UI-006_Sword_Texture.md) |
| UI-007 | UI | Невозможно пропустить анимацию | Minor | Medium | [Открыть](BugReports/UI-007_Skip_Animation.md) |
| UI-008 | UI | Не закреплённая кнопка паузы | Major | Medium | [Открыть](BugReports/UI-008_Pause_Button.md) |
| PERF-001 | Performance | Проседание FPS в диалогах | Major | High | [Открыть](BugReports/PERF-001_FPS_Drop.md) |
| FUNC-002 | Functional | Зависание при повторном прохождении | Critical | High | [Открыть](BugReports/FUNC-002_Game_Freeze.md) |

---

## 📊 Performance Testing
- [CSV-лог](performance-Tests/Hardware.20260921-183828.CSV)

---

## 💡 Предложения по улучшению
- Унифицировать шрифт, размер и степень пикселизации во всех сценах игры.
- Закрепить кнопку паузы.
- Увеличить чувствительность ползунка скорости текста.
- Разделить магазин и инвентарь.