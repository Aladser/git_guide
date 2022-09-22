# Состояния репозитория

&emsp; &ensp;```status``` — это еще одна важнейшая команд, показывающая информацию о текущем состоянии репозитория

&emsp; &ensp; Ввод ```status``` на новом репозитории должен выдать:

---

&ensp;```$ git status```

&ensp;On branch master

&ensp; No commits yet

&ensp; nothing to commit (create/copy files and use "git add" to track)

---
&emsp; &ensp;Добавим новый файл в репозитории. Статус:

---

&ensp;```$ git status```

&ensp;On branch master

&ensp; Your branch is up to date with 'origin/master'.

&ensp;Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        
&emsp; &ensp;&emsp; &ensp;&emsp; &ensp;&emsp; &ensp; 
<span style="color:red">modified: readme.md</span>

&ensp;Untracked files:
  
&ensp; (use "git add <file>..." to include in what will be committed)

&ensp;<span style="color:red">git_install.md</span>

&ensp;<span style="color:red">git_install.md</span>

&ensp;<span style="color:red">license.md</span>

&ensp;<span style="color:red">rep_status.md</span>

&ensp;<span style="color:red">"\321\202\320\265\321\201\321\202.txt"</span>


&ensp;no changes added to commit (use "git add" and/or "git commit -a")

---

Внесем изменения:

```git commit -m "тестирование докумнетации 1"```

Отправим изменения в удаленный репозиторий:


