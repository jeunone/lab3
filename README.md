# Лабораторная работа №3: Система контроля версий Git

## Студент: Попов Евгений
## Номер ИСУ: 505444
## Вариант: 505444

---

### Цель работы

Изучение основных команд git: `add`, `commint`, `merge`, `rebase`, `branch`, `checkout`


### Задания:

1) Добавьте строку "зачет" в файл `config.txt` и сделайте коммит
2) Измените файл `config.txt`, добавьте строку "не зачет" и сделайте коммит
3) Перейдите на ветку `'hotfix'`, добавьте строку "зачет" в файл `config.txt` и сделайте коммит
4) Посмотрите разницу между последними двумя коммитами и сохраните вывод в файл `diff.txt`
5) Откатитесь к 3-му коммиту на ветке `main`, измените файл `config.txt`, добавьте строку "зачет" и сделайте новый коммит
6) Перейдите на ветку `'hotfix'` и выполните `rebase` на `main`. Разрешите возможные конфликты
7) Слейте ветки `feature1` и `feature2` в `main`. Конфликт возникнет автоматически, разрешите его и сделайте merge-коммит
8) Создайте ветку `'release'` от `main` и слейте в неё все изменения

-1) Создайте аккаунт на github.com и оформите ваш репозиторий

После выполнения всех заданий сохраните историю всех коммитов в файл `history.txt`:


### Материалы 

1. https://www.youtube.com/watch?v=mJ-qvsxPHpY
2. https://youtu.be/XuFaQSW79rM?si=uIhKCiygX8q8ELSR
3. https://www.youtube.com/watch?v=VJm_AjiTEEc


---
Файл `history.txt`:
*   9033a84 Merge branch 'hotfix' into release
|\  
| * 086a553 step 4
| * cf4d46d add config.txt 5
| * a33aa73 add config.txt 4
* |   ee58799 feature2
|\ \  
| * | 5a37641 feature2 change
* | |   4fdad9d feature1
|\ \ \  
| |_|/  
|/| |   
| * | b50dce7 feature1 change
| |/  
* | 988c313 step 5
| | * 2f14615 second step
| | * 04469ac first
| |/  
| * 0cd0f91 add config.txt 5
| * ca2584b add config.txt 4
|/  
* c991f65 add config.txt 3
* bfd2ccb add config.txt 2
* 8b0b726 add config.txt 1
* 467fca1 init
