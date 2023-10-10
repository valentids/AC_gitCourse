# Задание

Система контроля версий позволяет сохранять историю развития кода, а также
обмениваться кодом между разработчиками, поэтому полезна при написании любой
программы.

Git — система управления версиями с распределенной архитектурой. В отличие от
некогда популярных систем вроде CVS и Subversion (SVN), где полная история
версий проекта доступна лишь в одном месте, в Git каждая рабочая копия кода сама
по себе является репозиторием. Это позволяет всем разработчикам хранить историю
изменений в полном объеме, особенности:

* распределенность, а значит можно создать репозиторий локально и сразу писать
  код с версионированием
* состоит из набора утилит командной строки, поэтому успешно портирована на все
  популярные платформы и для нее разработано множество графических интерфейсов
  на любой вкус и цвет
* поддерживается популярными хостингами репозиториев — GitHub, GitLab, Bitbucket
* поддерживается популярными IDE — Visual Studio, Visual Studio Code, Rider,
  WebStorm и многими другими

## Чтобы начать работать:

1. Заведи аккаунт на GitHub.com
2. Установить Git Bash и Visual Studio Code (графический интерфейс). Подходит
   для Linux, Mac и Windows.

## Задания:

Это проект консольного калькулятора.

1. Сделайте `fork`` этого репозитория.
2. Склонируйте себе свой форк.
3. Откройте проект в IDE и немного изучите его.
4. Выполните работу с репозиторием:
   1. Изучите коммиты начиная с `init commit`.
   2. Перейдите в ветку `matireals` и изучите по логу коммитов, что именно
   произошло в этой ветке.
   3. Переключитесь в ветку `test` и изучите по логу коммитов, что именно произошло в этой ветке.
   4. Создать ветку `mybranch1`. Переключитесь на эту ветку.
      1. Создайте файл `textFile.txt` с текстом `Hello my first work`
      2. Закомитить и за пушить
   5. Переключиться на ветку `main`
   6. Cоздать ветку `mybranch2`. Переключитесь на эту ветку.
      1. Создайте файл `textFile.txt` с текстом `Hello, my second work is great`
      2. Закомитить и за пушить
   7.  Смержить ветку `mybranch2` в `mybranch1`
   8.  Создать ветку `mybranchfinal` на остнове веткки `mybranch2`
   9.  Создайте файл `myWork.md`, внутри укажите вашу фамилию.
   10. В файле `myWork.md` напишите ответы на следующие вопросы:
      1. Сколько источников было в файле `Links.md` в коммите 245bcca7fd8622fbcca41b6cccb8cce43fb1c9f8
      2. Какой коммит добавил в репозиторий
      3. Сохраните файл
   11. Далее необходимо закомитить и за пушить иземенения которые вы сделали.
   12. Сделайте pull request с вашим файлом. Так я увижу, что вы сделали работу.
