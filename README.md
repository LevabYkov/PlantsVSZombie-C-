🌻 Plants vs Zombies: Console Edition 🧟 

Классическая битва растений и зомби в терминале! 
Текстовая стратегия в духе оригинальной PvZ с упором на тактику и управление ресурсами. 

🎮 Особенности 

- Полноценный геймплей с 4 уровнями сложности
- 10+ видов растений (от Подсолнуха до Горохострела Гатлинга)
- 4 типа зомби (обычные, спринтеры, гиганты) - Система волн атак
- Оптимизированная консольная графика (с эмодзи!)
- Управление без зависаний

⚙️ Технологии 

- Чистый C++ (стандарт 17)
- Библиотеки: `<unistd.h>`, `<termios.h>`

🚀 Запуск

Для запуска игры через бинарный файл необходимо скачать компилятор g++, а уже после в терминале запустить игру: "./имя файла".
Если же хотите компилировать ваш код в бинарник необходимо написать: "g++ main.cpp(путь к фалу) -o main(название файла". 
ВАЖНО: 
- КОД РАБОТАЕТ ТОЛЬКО НА ЛИНУКС!!!!!!!!!
- КОД РАБОТАЕТ ТОЛЬКО В ТЕРМИНАЛЕ ЛИНУКС(Если запустите в консоли QTCreator, то у вас не будет работать очистка терминала и будет вылазить ошибка. Это все из-за того, что терминал QtCreator не поддерживает все ANSI-коды)

📌 Правила

1. Собирайте солнце (🌞) для покупки растений
2. Останавливайте зомби до подхода к дому (🚜)
3. Открывайте новые растения после уровней

🌟 Для разработчиков

- Модульная архитектура
- Легкость добавления новых типов юнитов
- Чистый код с комментариями
