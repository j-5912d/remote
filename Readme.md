# Работа с удаленными репозиториями GIT HUB
1. Сначала необходимо создать аккаунт на GIT HUB
2. Создать локальный репозиторий
3. Создать удаленный репозиторий
4. Связать удалённый репозиторий с удалённым

Команды используемые для создания работы с GIT HUB
```
git remote add origin <ссылка предлагаемая GitHub>
git branch -M main
git remoute -v
```

```
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 705 bytes | 705.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/j-5912d/remote.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```