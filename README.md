# scripts
My bash scripts

Мои скрипты, используемые в процессе обучения в Школе 21 от Сбербанк

#### startup.sh
Скрипт для мониторинга оставшейся памяти на устройстве. При заполнении памяти больше критического значения, выводит оповещение в консоль, показывает папки наибольшего размера и предлагает очисить кеш Школы автоматически.    
Для лучшего эффекта добавьте скрипт в автозапуск, путем добавления в файл `~/.zshrc` строку `sh ~/<filepath>/startup.sh`, где filepath - путь до файла

#### clear_fucken_DSstore.sh
Простенький скрипт для удаления всех файлов .DS_Store во всех вложенных папках.

#### ps_generator.sh
Скрипт для генерации случайной последовательности чисел. Нужен для проекта push_swap.

#### aliases.txt
мой список aliases.