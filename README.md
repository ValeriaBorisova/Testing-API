[![Build status](https://ci.appveyor.com/api/projects/status/6b7r6sbeg25i6dim/branch/master?svg=true)](https://ci.appveyor.com/project/ValeriaBorisova/testing-api/branch/master)


* Task description 

``` https://github.com/netology-code/aqa-homeworks/tree/master/api-ci```

______________________________________________________

Task №1 - Setting up CI

Реализация проекта:
* Создан проект на базе Gradle
* Добавлен и адаптирован файл ```.appveyor.yml```
* Настроен проект на AppVeyor
* Создан ```Status Badge``` в проекте AppVeyor
* Проведена проверка фактического отбражения ```Status Badge``` путем принудительного падения теста
* В файл README.md размещен код для ```Status Badge```

____________________________________________________

Task №2 - JSON Schema
Реализация проекта:
* На базе проекта ```Task №1 - Setting up CI```  добавлена зависимость 
```
dependencies {
    testImplementation 'io.rest-assured:rest-assured:4.4.0'
    testImplementation 'io.rest-assured:json-schema-validator:4.4.0'
    testImplementation 'org.junit.jupiter:junit-jupiter:5.8.2'
    }
```
* Создан каталог ```resources``` в ```src/test``` и помещена туда Schema
* Настроен проект на AppVeyor
* Создан ```Status Badge``` в проекте AppVeyor
* Проведена проверка фактического отбражения ```Status Badge``` путем принудительного изменения в ```Schema``` 
* В файл README.md размещен код для ```Status Badge```
 
______________________________________________________

Результаты фактической проверки ```Status Badge``` - сборки CI:

```https://ci.appveyor.com/project/ValeriaBorisova/testing-api/history```
