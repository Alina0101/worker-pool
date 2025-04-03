# Worker Pool in Go
![Go Version](https://img.shields.io/badge/go-1.21+-blue.svg)
![License](https://img.shields.io/badge/license-GPLv3-green.svg)

Простая и эффективная реализация пула воркеров на горутинах для параллельной обработки задач. Позволяет ограничить количество одновременно выполняемых операций, идеально подходит для обработки URL, файлов или любых других задач, требующих контроля за параллелизмом.

**Ключевые особенности:**
- Фиксированное количество воркеров
- Безопасная передача задач через каналы
- Автоматическое распределение задач
- Простое API (Start/Stop/AddTask)

