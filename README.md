# Spore Admin Panel — облачная сборка

1. На github.com создай новый репозиторий (Create new repository, public или private).
2. Загрузи в него всё содержимое этой папки (Add file -> Upload files), включая папки `.github` и `src`.
3. Открой вкладку **Actions** -> "Build Spore mod DLL" -> **Run workflow**.
4. Когда сборка станет зелёной, открой запуск и внизу в **Artifacts** скачай `SporeAdminPanel` (в zip лежит `SporeAdminPanel.dll`).
5. Распакуй DLL в папку `mLibs` лаунчера модов Spore.

Если сборка красная: открой упавший шаг, скопируй текст ошибки и пришли мне.
