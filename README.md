# Лабораторная работа номер 2
## Часть первая

   1. Создайте пустой репозиторий на сервисе github.com (или gitlab.com, или bitbucket.com).
   2. Выполните инструкцию по созданию первого коммита на странице репозитория, созданного на предыдещем шаге.
   3. Создайте файл hello_world.cpp в локальной копии репозитория (который должен был появиться на шаге 2). Реализуйте программу Hello world на языке C++ используя плохой стиль кода. Например, после заголовочных файлов вставьте строку using namespace std;.
   4. Добавьте этот файл в локальную копию репозитория.
   5. Добавьте этот файл в локальную копию репозитория
   6. Изменитьте исходный код так, чтобы программа через стандартный поток ввода запрашивалось имя пользователя. А в стандартный поток вывода печаталось сообщение Hello world from @name, где @name имя пользователя.
   7. Закоммитьте новую версию программы. Почему не надо добавлять файл повторно git add?
   8. Запуште изменения в удалёный репозиторий.
   9. Проверьте, что история коммитов доступна в удалёный репозитории.
   
## Часть вторая

   1. В локальной копии репозитория создайте локальную ветку patch1.
   2. Внесите изменения в ветке patch1 по исправлению кода и избавления от using namespace std;.
   3. commit, push локальную ветку в удалённый репозиторий.
   4. Проверьте, что ветка patch1 доступна в удалёный репозитории.
   5. Создайте pull-request patch1 -> master.
   5. В локальной копии в ветке patch1 добавьте в исходный код комментарии.
   6. commit, push.
   7. Проверьте, что новые изменения есть в созданном на шаге 5 pull-request
   8. В удалённый репозитории выполните слияние PR patch1 -> master и удалите ветку patch1 в удаленном репозитории.
   9. Локально выполните pull.
   10. С помощью команды git log просмотрите историю в локальной версии ветки master.
   11. Удалите локальную ветку patch1.

## Часть третья

   1. Создайте новую локальную ветку patch2.
   2. Измените code style с помощью утилиты clang-format. Например, используя опцию -style=Mozilla.
   3. commit, push, создайте pull-request patch2 -> master.
   4. В ветке master в удаленном репозитории измените комментарии, например, расставьте знаки препинания, переведите комментарии на другой язык.
   5. Убедитесь, что в pull-request появились конфликтны.
   6. Для этого локально выполните pull + rebase (точную последовательность команд, следует узнать самостоятельно). Исправьте конфликты.
   7. Сделайте force push в ветку patch2
   8. Убедитель, что в pull-request пропали конфликтны.
   9. Вмержите pull-request patch2 -> master.

## Выполнение Лабораторной работы
### Часть первая
#### Задание номер 1 (Создайте пустой репозиторий на сервисе github.com (или gitlab.com, или bitbucket.com).
#### Задание номер 2 (Выполните инструкцию по созданию первого коммита на странице репозитория, созданного на предыдещем шаге.
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-25%2017-30-10.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-25%2017-30-31.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-25%2017-30-53.png)

get init - создание пустого локального репозитория

git remote add origin ... - добавление удаленного репозитория и присвоение ему названия

git pull origin main - синхронизация с удалённым репозиторием


#### Задание номер 3 (Создайте файл hello_world.cpp в локальной копии репозитория (который должен был появиться на шаге 2). Реализуйте программу Hello world на языке C++ используя плохой стиль кода. Например, после заголовочных файлов вставьте строку using namespace std;)

#### Задание номер 4 (Добавьте этот файл в локальную копию репозитория)

#### Задание номер 5 (Добавьте этот файл в локальную копию репозитория)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-27%2013-29-32.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-27%2013-30-02.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-27%2013-30-44.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-27%2013-31-08.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-01%2021-50-51.png)

git status - просмотр текущих изменений

git add - добавить файл в локальный репозиторий

git config --global user.email - настройка адреса электронной почты

git commit -m - описание коммита в локальном репозитории

git push - отправка изменений в удалённый репозиторий

### Часть вторая
#### Задание номер 1 (В локальной копии репозитория создайте локальную ветку patch1.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-10%2018-35-52.png)

#### Задание номер 2 (Внесите изменения в ветке patch1 по исправлению кода и избавления от using namespace std;)

#### Задание номер 3 (commit, push локальную ветку в удалённый репозиторий.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-12%2009-21-48.png)

#### Задание номер 4 (Проверьте, что ветка patch1 доступна в удалёный репозитории.)

#### Задание номер 5 (В локальной копии в ветке patch1 добавьте в исходный код комментарии.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-12%2009-27-58.png)

#### Задание номер 6 ( commit, push.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-10%2018-39-23.png)

#### Задание номер 7 (Проверьте, что новые изменения есть в созданном на шаге 5 pull-request)

#### Задание номер 8 (В удалённый репозитории выполните слияние PR patch1 -> master и удалите ветку patch1 в удаленном репозитории.)

#### Задание номер 9 ( Локально выполните pull.)




### Часть третья
#### Номер задания 1 ( Создайте новую локальную ветку patch2.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-11%2017-05-14.png)

#### Задание номер 2 (Измените code style с помощью утилиты clang-format. Например, используя опцию -style=Mozilla.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-11%2017-15-30.png)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-11%2017-32-38.png)

style= - загрузка конфигурации стиля

clang-format -i - форматирование файла на место

#### Задание номер 3 (commit, push, создайте pull-request patch2 -> master.)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-11%2017-18-50.png)

#### Задание номер 4 (Проверьте, что ветка patch1 доступна в удалёный репозитории.)
В ветке master в удаленном репозитории измените комментарии, например, расставьте знаки препинания, переведите комментарии на другой язык.

#### Задание номер 5 (Убедитесь, что в pull-request появились конфликты)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-12%2008-58-58.png)

#### Задание номер 6 (Убедитесь, что в pull-request появились конфликтны)

#### Задание номер 7 (Сделайте force push в ветку patch2)
![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-12%2009-07-05.png)

git push --force удаляет из ветки на сервере все коммиты, которых нет в локальной версии, и записывает новые

#### Задание номер 8 (Убедитель, что в pull-request пропали конфликтны.)

#### Задание номер 9 (Вмержите pull-request patch2 -> master.)

![image](https://github.com/BogdanKoval4uk/-laboratornay2/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-05-12%2009-10-46.png)



