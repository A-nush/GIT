GIT_branch_HW_3.md
1. На локальном репозитории сделать ветки для:
- Postman === **git branch Postman**
- Jmeter === **git branch Jmeter**
- CheckLists === **git branch Checklists**
- Bag Reports === **git branch Bag_Reports**
- SQL === **git branch SQL**
- Charles === **git branch Charles**
- Mobile testing === **git branch Charles**

2. Запушить все ветки на внешний репозиторий 
+ **git push origin --all**
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта 
+ **git checkout Bag_Reports**
+ **vim bag_report.txt** + description of the report
4. Запушить структуру багрепорта на внешний репозиторий
+ **git add bag_report.txt**
+ **git commit -m bag_report.txt**
+ **git push --set-upstream origin Bag_Reports**
5. Вмержить ветку Bag Reports в Main
+ **git checkout main**
+ **git merge Bag_Reports**
6. Запушить main на внешний репозиторий
+ **git push**   
7. В ветке CheckLists набросать структуру чек листа
+ **git checkout checklist**
+ **vim check_list.md** + description of the steps
8. Запушить структуру на внешний репозиторий
+ **git add check_list.md**
+ **git commit -m check_list.md**
+ **git push --set-upstream origin Checklist**
9.  На внешнем репозитории сделать Pull Request ветки CheckLists в main
+ **create pull request -- merge pull request -- confirm merge**     
10. Синхронизировать Внешнюю и Локальную ветки Main
+ **git checkout main**
+ **git pull**
