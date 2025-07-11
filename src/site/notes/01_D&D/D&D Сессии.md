---
{"dg-publish":true,"permalink":"/01-d-and-d/d-and-d-sessii/","created":"2024-11-09T09:06:49.577+03:00","updated":"2025-06-29T23:14:03.711+03:00"}
---

**[[01_D&D/D&D Сессии\|<< Главная]]** 

```meta-bind-button
label: Сегодняшняя заметка
icon: calendar
hidden: false
class: ""
tooltip: Создать новую заметку сессии
id: create-session-note
style: primary
actions:
  - type: inlineJS
    code: |
      const folderPath = "01_D&D/Сессии";
      const fileName = `${new Date().toISOString().split('T')[0]}.md`;
      const templatePath = "templates/Сессия D&D.md";
      
      async function createNote() {
        const { workspace, vault } = app;
        const template = await vault.adapter.read(templatePath);
        const newFilePath = `${folderPath}/${fileName}`;
        
        if (await vault.adapter.exists(newFilePath)) {
          await workspace.openLinkText(newFilePath, "", false);
        } else {
          await vault.create(newFilePath, template);
          await workspace.openLinkText(newFilePath, "", false);
        }
      }

      createNote();
  - type: command
    command: "Templater: Replace templates in the active file"

```

---
	Заметки о сессиях с пометкой "🛑" не заполнены. 
## 📚 Сессии 

> 🧭 Обзор всех игровых сессий. Нажмите на название сессии, чтобы узнать подробности.

| File                                                                                          | Номер Сессии |
| --------------------------------------------------------------------------------------------- | ------------ |
| [[01_D&D/Сессии/2025-06-29\|2025-06-29]]                                                   | 1            |
| [[01_D&D/Сессии/2025-01-13\|2025-01-13]]                                                   | \-           |
| [[01_D&D/Сессии/2024-12-19\|2024-12-19]]                                                   | \-           |
| [[01_D&D/Сессии/2024-12-09\|2024-12-09]]                                                   | \-           |
| [[01_D&D/Сессии/2024-12-05\|2024-12-05]]                                                   | \-           |
| [[01_D&D/Сессии/2024-11-25\|2024-11-25]]                                                   | \-           |
| [[01_D&D/Сессии/2024-11-18\|2024-11-18]]                                                   | \-           |
| [[01_D&D/Сессии/2024-11-14\|2024-11-14]]                                                   | \-           |
| [[01_D&D/Сессии/2024-11-10. Чульт. Заметки о сессии\|2024-11-10. Чульт. Заметки о сессии]] | \-           |
| [[01_D&D/Сессии/2024-11-10. Чульт\|2024-11-10. Чульт]]                                     | \-           |
| [[01_D&D/Сессии/2024-11-10\|2024-11-10]]                                                   | \-           |
| [[01_D&D/Сессии/2024-04-29. Чульт\|2024-04-29. Чульт]]                                     | 45           |
| [[01_D&D/Сессии/2024-04-15. Чульт\|2024-04-15. Чульт]]                                     | 44           |
| [[01_D&D/Сессии/2024-04-08. Чульт\|2024-04-08. Чульт]]                                     | 43           |
| [[01_D&D/Сессии/2024-04-01. Чульт\|2024-04-01. Чульт]]                                     | 42           |
| [[01_D&D/Сессии/2024-03-25. Чульт\|2024-03-25. Чульт]]                                     | 41           |
| [[01_D&D/Сессии/2024-03-18. Чульт\|2024-03-18. Чульт]]                                     | 40           |
| [[01_D&D/Сессии/2024-03-11. Чульт\|2024-03-11. Чульт]]                                     | 39           |
| [[01_D&D/Сессии/2024-03-04. Чульт\|2024-03-04. Чульт]]                                     | 38           |
| [[01_D&D/Сессии/2024-02-26. Чульт\|2024-02-26. Чульт]]                                     | 37           |
| [[01_D&D/Сессии/2024-02-12. Чульт\|2024-02-12. Чульт]]                                     | 36           |
| [[01_D&D/Сессии/2024-02-06. Чульт\|2024-02-06. Чульт]]                                     | 35           |
| [[01_D&D/Сессии/2024-01-29. Чульт\|2024-01-29. Чульт]]                                     | 34           |
| [[01_D&D/Сессии/2024-01-22. Чульт\|2024-01-22. Чульт]]                                     | 33           |
| [[01_D&D/Сессии/2024-01-15. Чульт\|2024-01-15. Чульт]]                                     | 32           |
| [[01_D&D/Сессии/2024-01-08. Чульт\|2024-01-08. Чульт]]                                     | 31           |
| [[01_D&D/Сессии/2023-12-25. Чульт\|2023-12-25. Чульт]]                                     | 30           |
| [[01_D&D/Сессии/2023-12-18. Чульт\|2023-12-18. Чульт]]                                     | 29           |
| [[01_D&D/Сессии/2023-12-11. Чульт\|2023-12-11. Чульт]]                                     | 28           |
| [[01_D&D/Сессии/2023-12-04. Чульт\|2023-12-04. Чульт]]                                     | 27           |
| [[01_D&D/Сессии/2023-11-27. Чульт 🛑\|2023-11-27. Чульт 🛑]]                               | 26           |
| [[01_D&D/Сессии/2023-11-20. Чульт 🛑\|2023-11-20. Чульт 🛑]]                               | 25           |
| [[01_D&D/Сессии/2023-11-13. Чульт 🛑\|2023-11-13. Чульт 🛑]]                               | 24           |
| [[01_D&D/Сессии/2023-11-06. Чульт 🛑\|2023-11-06. Чульт 🛑]]                               | 23           |
| [[01_D&D/Сессии/2023-10-30. Невервинтер 🛑\|2023-10-30. Невервинтер 🛑]]                   | 22           |
| [[01_D&D/Сессии/2023-10-23. Невервинтер 🛑\|2023-10-23. Невервинтер 🛑]]                   | 21           |
| [[01_D&D/Сессии/2023-10-16. Невервинтер 🛑\|2023-10-16. Невервинтер 🛑]]                   | 20           |
| [[01_D&D/Сессии/2023-10-09. Невервинтер 🛑\|2023-10-09. Невервинтер 🛑]]                   | 19           |
| [[01_D&D/Сессии/2023-10-02. Невервинтер 🛑\|2023-10-02. Невервинтер 🛑]]                   | 18           |
| [[01_D&D/Сессии/2023-09-25. Невервинтер 🛑\|2023-09-25. Невервинтер 🛑]]                   | 17           |
| [[01_D&D/Сессии/2023-09-18. Невервинтер 🛑\|2023-09-18. Невервинтер 🛑]]                   | 16           |
| [[01_D&D/Сессии/2023-09-11. Невервинтер 🛑\|2023-09-11. Невервинтер 🛑]]                   | 15           |
| [[01_D&D/Сессии/2023-09-04. Невервинтер 🛑\|2023-09-04. Невервинтер 🛑]]                   | 14           |
| [[01_D&D/Сессии/2023-08-28. Невервинтер 🛑\|2023-08-28. Невервинтер 🛑]]                   | 13           |
| [[01_D&D/Сессии/2023-08-21. Невервинтер\|2023-08-21. Невервинтер]]                         | 12           |
| [[01_D&D/Сессии/2023-08-19. Невервинтер\|2023-08-19. Невервинтер]]                         | 11           |
| [[01_D&D/Сессии/2023-08-07. Невервинтер\|2023-08-07. Невервинтер]]                         | 10           |
| [[01_D&D/Сессии/2023-07-31. Невервинтер\|2023-07-31. Невервинтер]]                         | 9            |
| [[01_D&D/Сессии/2023-07-24. Невервинтер\|2023-07-24. Невервинтер]]                         | 8            |
| [[01_D&D/Сессии/2023-07-17. Невервинтер\|2023-07-17. Невервинтер]]                         | 7            |

{ .block-language-dataview}

---