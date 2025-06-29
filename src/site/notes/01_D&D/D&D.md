---
{"dg-publish":true,"permalink":"/01-d-and-d/d-and-d/","tags":["gardenEntry"],"created":"2024-11-09T09:06:49.579+03:00","updated":"2025-06-29T22:48:56.949+03:00"}
---


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
[ 🤖 ChatGPT помощник 🤖](https://chat.openai.com/g/g-MHo60ZEsx-note-assistant) по составлению заметок в этом формате. Ему нужно скинуть дату сессии, номер сессии и свои заметки в любом формате, в ответ он сгенерирует страницу по своему шаблону. 
[🚀 Deploy 🚀](https://vercel.com/elks-projects/elk21-dnd-notes-h8pc)
[[04_Research/Промпт для создания рассказа по сессии ДнД\|Промпт для создания рассказа по сессии ДнД]]
[[01_D&D/Записки Элька/Записки Элька\|Записки Элька]]

[[Кампания в Глубоководье\|Кампания в Глубоководье]]

---

 📚 [[01_D&D/D&D Сессии\|Сессии]] 
 🧙‍♂️ [[01_D&D/D&D Персонажи\|Персонажи]] 
 🏰 [[01_D&D/D&D Локации\|Локации]]
 👥 [[01_D&D/D&D Игроки\|Игроки]]

---
#### Последние 3 сессии

| File                                        | Номер Сессии |
| ------------------------------------------- | ------------ |
| [[01_D&D/Сессии/2025-06-29\|2025-06-29]] | 1            |
| [[01_D&D/Сессии/2025-01-13\|2025-01-13]] | \-           |
| [[01_D&D/Сессии/2024-12-19\|2024-12-19]] | \-           |

{ .block-language-dataview}

#### Сырые заметки

| File                                                                                           |
| ---------------------------------------------------------------------------------------------- |
| [[01_D&D/Заметки/2025-01-20. Чульт\|2025-01-20. Чульт]]                                     |
| [[01_D&D/Заметки/2025-01-13. Чульт. Заметки о сессии\|2025-01-13. Чульт. Заметки о сессии]] |
| [[01_D&D/Заметки/2024-12-19. Чульт. Заметки о сессии\|2024-12-19. Чульт. Заметки о сессии]] |

{ .block-language-dataview}
---
![D&D Mindmap 1.png](/img/user/01_D&D/img/D&D%20Mindmap%201.png)

#### Последние обновленные страницы

| File                                        | Обновлено                   |
| ------------------------------------------- | --------------------------- |
| [[01_D&D/D&D\|D&D]]                      | 10:48 PM - June 29, 2025    |
| [[01_D&D/Сессии/2025-06-29\|2025-06-29]] | 10:48 PM - June 29, 2025    |
| [[templates/Сессия D&D\|Сессия D&D]]     | 10:46 PM - June 29, 2025    |
| [[Напака\|Напака]]                       | 8:57 PM - January 13, 2025  |
| [[01_D&D/Сессии/2025-01-13\|2025-01-13]] | 8:00 PM - January 13, 2025  |
| [[01_D&D/Сессии/2024-12-19\|2024-12-19]] | 8:33 PM - December 19, 2024 |
| [[01_D&D/Сессии/2024-12-09\|2024-12-09]] | 8:08 PM - December 09, 2024 |
| [[01_D&D/Сессии/2024-12-05\|2024-12-05]] | 8:43 PM - December 05, 2024 |
| [[01_D&D/Сессии/2024-11-25\|2024-11-25]] | 7:55 PM - November 25, 2024 |
| [[01_D&D/Сессии/2024-11-18\|2024-11-18]] | 8:11 PM - November 18, 2024 |

{ .block-language-dataview}
---
