# Py-15 Git

Цей проєкт містить два Python-файли. У 'mymod.py' є функції для підрахунку рядків і символів,
а 'main.py' імпортує цей модуль і запускає перевірку.

Щоб запустити програму, виконайте команду:

```bash
python3 main.py
```

Папка '__pycache__/' не відображається в 'git status', тому що вона вказана у файлі '.gitignore',
який наказує Git ігнорувати цю папку.

## My history
5308b15 Add README.md
96a52f4 Add my module and the script that uses it
4a50f65 Add .gitignore

## AI log: 
використовувала для детальнішого пояснення виводу термінала 
та розуміння того, що роблять команди Git

## How to run

Run the program from the terminal:

```bash
python3 main.py
```
## Errors:
(.venv) alina@MacBook-Air-Alina py-15-git % git commit -m "Test error"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Git повідомляє, що README.md змінений, але не доданий до staging area

Наступна помилка: 
(.venv) alina@MacBook-Air-Alina PycharmProjects % git status
fatal: not a git repository (or any of the parent directories): .git

Git повідомляє, що папка PycharmProjects не є Git-репозиторієм

## Pull request

https://github.com/AlinaRadchenko/py-15-git/pull/1?utm_source=chatgpt.com