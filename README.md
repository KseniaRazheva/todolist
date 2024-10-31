# todolist

## как создать новый проект

создала на [гитхабе](https://github.com/KseniaRazheva?tab=repositories) новый репозиторий (new, Repository name, Add a README file)<br>
открываю на компьютере общую папку гитхаба через вскод (терминал code .), надо стянуть изменения

```
git clone https://github.com/KseniaRazheva/todolist.git
```

в моей папке гитхаб на компьютере появилась папка которую я создала на гитхабе и теперь туда можно писать код, а потом комитить

## как комитить
```
git status 
git add . 
git status 
git commit -m "add/update/return files sass l.61" 
git push -u origin main
// в случае неудачи git checkout .
```

## как начать проект на тайпскрипте 
$npx create-react-app my-app --template typescript
(после команды создается папка my-app)
(узнать как использовать ярн)
$cd my-app
$npm start
(сборщик вебпак)
открывается на http://localhost:3000/
(todolist будет похож на trello)
точка входа index.tsx
