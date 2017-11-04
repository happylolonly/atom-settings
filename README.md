##  Сохраненные настройки Atom


Для востановления https://stackoverflow.com/questions/30006827/how-to-save-atom-editor-config-and-list-of-packages-installed

Сохранение:
´apm list --installed --bare > ~/.atom/package.list´

Востановление:
´apm install --packages-file ~/.atom/package.list´


или через package-sync
