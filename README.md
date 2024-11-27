# test-git

1.  git status
2.  git add(files) / git add. - добавляет в STAGE
3.  git commit -m 'comment'
4.  git log --oneline
5.  git push (rep_link) (branch name)
6.  git reset (index.html)
7.  git diff - проверяет изменения
8.  git reset --hard - отменяет все изменения на начальный уровень и отменяет изменения в статусе

9.  git branch - просмотр веток
    git branch -d develop - удалить ветку с локального репозитория
10. git checkout main - перейти на ветку
11. git pull origin main - получить изменения из ветки гитхаб

12. - 1 способ через пулл реквест на гит хаб

    - 2 способ через
      (локальные изменения)
      переходим на ветку , в которую будем делать merge
      git merge feature/main-page

           (далее пушим на гитхаб)

    git push origin main
    (и удаляем ветку из гитхаба лишнюю) (и удаляем ветку из локального лишнюю)
