# Лабораторная работа №3: Система контроля версий Git

## Студент: Попов Евгений
## Номер ИСУ: 505444
## Вариант: 505444

---

### Цель работы

Изучение основных команд git: `add`, `commint`, `merge`, `rebase`, `branch`, `checkout`

### Выполненные задания

1.  Добавлена строка "зачет" и сделан коммит
2.  Добавлена строка "не зачет" и сделан коммит
3.  Создана/использована ветка `hotfix` для добавления "зачет"
4.  Создан файл `diff.txt` с разницей между коммитами
5.  Выполнен откат и создан новый коммит на ветке `main`
6.  Выполнен `rebase` ветки `hotfix` на `main` с решением конфликта
7.  Ветки `feature1` и `feature2` слиты в `main` с решением конфликта
8.  Создана финальная ветка `release` и слиты все изменения

### Материалы 

1. https://www.youtube.com/watch?v=mJ-qvsxPHpY
2. https://youtu.be/XuFaQSW79rM?si=uIhKCiygX8q8ELSR
3. https://www.youtube.com/watch?v=VJm_AjiTEEc

---
Файл history.txt:
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
