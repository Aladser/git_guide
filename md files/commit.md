# Внесение изменений

```git add .```

```git commit -m "create repository"```

```git push -u origin master```

   В команде git push мы использовали ключ -u. Данный ключ используется для того, чтобы связать локальную ветку master с удаленной origin/master (в нашем случае удаленной ветки не существовало, она автоматически была создана). Так как связь установлена, то последующие выполнения git push из ветки мастер можно выполнять без указания веток. То есть вместо git push origin master, можно просто выполнять команду git push.

&emsp; &ensp;Можно посмотреть историю коммитов командой**

```git log```

&emsp; &ensp;Игнорирование изменений в файлах
```git update-index --assume-unchanged application/config/database.php```

всю папку:

```git update-index --assume-unchanged application/config/*```


