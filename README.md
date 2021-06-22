# @tobertia/lab-tslint

Не надо его коммитить в package.json он в репе не нужен

`npm i -D @tobertia/lab-tslint`


В нужной папке создаем файлик `tslint.json` с содержимым
```
{
    "extends": "@tobertia/lab-tslint"
}
```
Ты великолепен

PS линтовать лучше используя конфиг в корне вашего проекта например: `ng lint --tslint-config ./tslint.json`, а то похаваешь варнингов
