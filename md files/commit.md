# Внесение изменений

```git add .```

```git commit -m "описание"```

```git push -u origin master```

   В команде git push мы использовали ключ -u. Данный ключ используется для того, чтобы связать локальную ветку master с удаленной origin/master. Так как связь установлена, то последующие выполнения git push из ветки мастер можно выполнять без указания веток.

&emsp; &ensp;Можно посмотреть историю коммитов командой

```git log```

&emsp; &ensp;Игнорирование изменений в файлах:

```git update-index --assume-unchanged application/config/database.php```

&emsp; &ensp;всю папку:

```git update-index --assume-unchanged application/config/*```


