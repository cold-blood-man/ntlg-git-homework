# Домашнее задание к занятию "`GIT`" - `Мартынов Андрей`
### Задание 1
##### Что нужно сделать:
1. Зарегистрируйте аккаунт на GitHub.
2. Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
3. Склонируйте репозиторий, используя https протокол `git clone ....`
4. Перейдите в каталог с клоном репозитория.
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email` johndoe@example.com.
6. Выполните команду git status и запомните результат.
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.
11. Ещё раз выполните команды `git diff` и `git diff --staged`.
12. Теперь можно сделать коммит `git commit -m 'First commit'`.
13. Сделайте `git push origin master`.

###### В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
---
1. Зарегистрировал аккаунт на GitHub, создал новый public репозиторий с README.md. Добавил в аккаунт открытый SSH ключ для возможности работы с репозиторием локально и синхронизации изменений.
2. Клонировал созданный репозиторий.  ![Скриншот 1](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen01.png)
3. Выполнил первоначальную настройку GIT, затем выполнил команду `git status`.  ![Скриншот 2](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen02.png)
4. Внёс изменения в файл README.md и выполнил команды `git status`, `git diff` и `git diff --staged`.  ![Скриншот 3](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen03.png)
5. Выполнил команду `git add README.md` и повторил команды из п. 4.  ![Скриншот 4](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen04.png)
6. Сделал коммит и запушил изменения на GitHub.  ![Скриншот 5](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen05.png)
7. Добавляю [ссылку](https://github.com/cold-blood-man/ntlg-git-hw1/commit/d583cb82c946e1b511cda951c1e33aa7712d7b00) на сделанный коммит.

---
---

### Задание 2
##### Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
2. Добавьте файл .gitignore в следующий коммит git add....
3. Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
4. Сделайте коммит и пуш.

###### В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
---
1. Добавил файл `.gitignore` и выполнил `git status`.  ![Скриншот 6](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen06.png)
2. Добавил файл в следующий коммит: `git add .gitignore`.  ![Скриншот 7](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen07.png)
3. Добавил в файл `.gitignore` необходимые условия. Условие __*.рус__ добавил в русской и английской раскладке (на всякий случай).  ![Скриншот 8](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen08.png)
4. Делаем коммит и пуш внесённых изменений в GitHub.  ![Скриншот 9](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen09.png)
5. Добавляю [ссылку](https://github.com/cold-blood-man/ntlg-git-hw1/commit/b8c5b301941633f49d79342b450f0f85256c309e) на сделанный коммит.

---
---

### Задание 3
##### Что нужно сделать:

1. Создайте новую ветку dev и переключитесь на неё.
2. Создайте в ветке dev файл `test.sh` с произвольным содержимым.
3. Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
4. Переключитесь на основную ветку.
5. Добавьте файл `main.sh` в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
6. Сделайте мердж dev ветки в основную с помощью `git merge dev`. Напишите осмысленное сообщение в появившееся окно комита.
7. Сделайте пуш в основной ветке.
8. Не удаляйте ветку dev.

###### В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.
---
1. Создали новую ветку dev и переключились на неё.  ![Скриншот 10](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen10.png)
2. Создал файл `test.sh`, сделал коммит и пуш в GitHub. Таким образом в удалённом репозитории появилась новая ветка dev.  ![Скриншот 11](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen11.png)
3. Сделал 2 коммита в ветке dev, переключился в ветку main и создал в ней файл `main.sh`. Затем закоммитил и запушил изменения.  ![Скриншот 12](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen12.png)
4. Делаем merge ветки dev в ветку main и пушим изменения в удалённый репозиторий.  ![Скриншот 13](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen13.png)
5. Прилагаю [ссылку](https://github.com/cold-blood-man/ntlg-git-hw1/network) на граф коммитов и его скриншот.  ![Скриншот 14](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen14.png)

---
---

### Задание 4*
##### Сэмулируем конфликт. Перед выполнением изучите документацию.
##### Что нужно сделать:

1. Создайте ветку conflict и переключитесь на неё.
2. Внесите изменения в файл test.sh.
3. Сделайте коммит и пуш.
4. Переключитесь на основную ветку.
5. Измените ту же самую строчку в файле test.sh.
6. Сделайте коммит и пуш.
7. Сделайте мердж ветки conflict в основную ветку и решите конфликт так, чтобы в результате в файле оказался код из ветки conflict.

###### В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.
---
1. Создал новую ветку conflictб внёс изменения в `test.sh`, сделал коммит и пуш.  ![Скриншот 15](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen15.png)
2. Создадим предпосылки для конфликта, внесём изменения в тот же файл в ветке main и закоммитим их.  ![Скриншот 16](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen16.png)
3. Мерджим ветку conflict в ветку main и получаем конфликт.  ![Скриншот 17](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen17.png)
4. При решении устранении конфликта в программе типа Visual Studio Code достаточно нажать кнопку `Accept Incoming Changes` и на выходе получим разрешение конфликта в пользу данных из ветки conflict. Этот вариант очень прост. Попробуем разрешить конфликт с помощью команд git.  ![Скриншот 18](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen18.png)
5. Сначала выполним команду `git checkout --conflict=diff3 test.sh`, чтобы получить полную картину 3-х вариантов изменений. Здесь base - это начальный вариант в ветке main, ours - измененный нами файл в ветке main, theirs - сливаемые изменения из ветки conflict. Задача состоит в том, чтобы конфликт был разрешён в пользу изменений из ветки conflict. В этом нам поможет команда `git checkout --theirs test.sh`, которая уберёт конфликтующие изменения и оставит только сливаемые из ветки conflict.  ![Скриншот 19](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen19.png)
6. Изменения внесены, теперь по известному пути: add, commit, push.  ![Скриншот 20](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen20.png)
7. Прилагаю [ссылку](https://github.com/cold-blood-man/ntlg-git-hw1/network) на граф коммитов и его скриншот.  ![Скриншот 21](https://github.com/cold-blood-man/ntlg-git-homework/blob/main/pics/screen21.png)
