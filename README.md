# Модуль и его сборка
Модуль живет в projects/lib/src/lib

Сборка ng build --project=lib

После этого содержимое файла dist.lib/bundles/lib.umd.js скопировать в assets/compiled-module.js

Запустить

#  Гду собака порылась?
Лэйаут хитрый, аутлеты вложены. Поэтому роутер приходится хитро патчить. При переходе на роуты динамического модуля -
 все ломается. Если раскомментить строку app.module:65 - все заработает. Но это хак. Мб можно как-то иначе?
 