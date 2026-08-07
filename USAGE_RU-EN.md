# Инструкция по использованию / User Guide

## Русский

### Первый запуск

1. Откройте приложение.
2. Перейдите во вкладку **Прайс** и добавьте виды работ с ценами.
3. Во вкладке **Клиенты** добавьте организации, адреса и контакты.
4. Нажмите **+ Добавить обращение**, заполните дату и причину вызова.
5. Добавьте работы из прайса, укажите количество и множитель.
6. Нажмите **Сохранить**.

Если обращение создавать не нужно, нажмите **Отмена**. При редактировании ранее сохранённого обращения его можно удалить кнопкой **Удалить** с подтверждением.

### Прайс-лист

Во вкладке **Прайс** можно создавать, редактировать и удалять работы.

В разделе **Настройки → Прайс-лист** доступны:

- **Выгрузить** — создаёт текстовый файл, по одной работе на строку;
- **Загрузить** — заменяет текущий прайс данными из текстового файла.

Формат строки:

```text
Настройка Wi-Fi    1500
Установка программы    800,50
```

Название и цена разделяются табуляцией, точкой с запятой или вертикальной чертой. При импорте одинаковые названия сохраняют свои идентификаторы.

### Резервная копия

Кнопка **⬇ Экспорт** в верхней панели сохраняет всю базу в JSON. Кнопка **⬆ Импорт** восстанавливает базу из JSON-файла.

Перед импортом текущие данные заменяются. После импорта доступен короткий откат операции, но регулярные резервные копии всё равно обязательны.

### Счёт

Выберите фильтр **Не оплачено**, откройте карточку клиента и нажмите **📄 Счёт**. Ненужные работы можно снять галочками. Затем используйте **Поделиться** или **Скопировать**.


## English

### First launch

1. Open the app.
2. Go to the **Price list** tab and add work items with prices.
3. In the **Clients** tab, add organizations, addresses and contacts.
4. Tap **+ Add request**, then enter the date and service reason.
5. Add work items from the price list, with quantity and multiplier.
6. Tap **Save**.

If you decide not to create the request, tap **Cancel**. An existing request can be deleted from the edit screen with the **Delete** button and confirmation.

### Price list

The **Price list** tab lets you create, edit and delete work items.

In **Settings → Price list**:

- **Export** creates a plain-text file with one work item per line;
- **Import** replaces the current price list with the text file contents.

Example:

```text
Wi-Fi setup    1500
Software installation    800.50
```

The name and price may be separated by a tab, semicolon or vertical bar. Existing IDs are preserved when imported names match existing names.

### Backup

Use **⬇ Export** in the top bar to save the complete database as JSON. Use **⬆ Import** to restore a JSON backup.

The import replaces current data. A short rollback option is shown after import, but regular backups are recommended.

### Invoice

Select the **Unpaid** filter, open a client card and tap **📄 Invoice**. Unneeded work items can be unchecked. Then use **Share** or **Copy**.

