# IT Аутсорс / IT Outsource

## Русский

Офлайн-приложение для учёта клиентов, обращений, выполненных работ и расчёта стоимости выездного IT-специалиста.

Приложение работает как одностраничный HTML-инструмент в браузере и как Android APK на базе Capacitor. Данные хранятся локально на устройстве; предусмотрены резервное копирование и восстановление.

### Возможности

- клиенты, контакты, адреса, заметки и множитель цены;
- прайс-лист с поиском, сортировкой, текстовым экспортом и импортом;
- обращения со статусами, работами, количеством, множителем и ручной суммой;
- отмена создания и удаление обращений;
- счёт по неоплаченным обращениям;
- импорт и экспорт полной базы JSON;
- светлая и тёмная тема;
- Android APK и браузерная версия без внешней базы данных.

### Версия

Текущая версия: **V1.23**.

## English

Offline application for managing clients, service requests, performed work and pricing for a field IT specialist.

The app runs as a single-page HTML application in a browser and as an Android APK powered by Capacitor. Data is stored locally on the device, with full JSON backup and restore support.

### Features

- clients, contacts, addresses, notes and price multipliers;
- searchable and sortable price list with text export/import;
- service requests with statuses, work items, quantities, multipliers and manual totals;
- cancel request creation and delete existing requests;
- invoices for unpaid requests;
- full database JSON import/export;
- light and dark themes;
- Android APK and browser version with no external database.


### Version

Current version: **V1.23**.

## Публикация / Publishing

The repository intentionally excludes local Android build caches, `node_modules`, `local.properties`, and signing credentials. A release build requires your own keystore; never commit the keystore password or private key.
