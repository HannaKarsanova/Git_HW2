# Git_HW2
### 1. На локальном репозитории сделать ветки для:
```
- Postman *git branch Postman*
- Jmeter  *git branch Jmeter*
- CheckLists *git branch CheckLists*
- Bag Reports *git branch BagReports*
- SQL *git branch SQL*
- Charles *git branch Charles*
- Mobile testing *git branch MobileTesting*
```  
2. Запушить все ветки на внешний репозиторий - *git push —all*
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта - 
	*git checkout BagReports
	cat > Star.txt*
```	
  ID
Severity
Priority
Title
Environment
Precondition
STR
AR
ER
Attachment
```
4. Запушить структуру багрепорта на внешний репозиторий - 
	*git add .
	git commit -m «new»
	git push —set-upstream origin BagReports*
5. Вмержить ветку Bag Reports в Main
	*git checkout main
	git merge BagReport*
6. Запушить main на внешний репозиторий.
	*git push*
7. В ветке CheckLists набросать структуру чек листа.
	*git checkout Checklists
	cat > STcl.txt*
  ```
	Title 
Environment
Precondition
Steps to reproduce
ER
AR
Status
Attachment
```
8. Запушить структуру на внешний репозиторий 
	*git add .
	git commit -m «CheckLists»
	git push --set-upstream origin CheckLists*
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
	зайти на ветку *СheckLists*
	нажать *Compare pull request*
	далее прописать название и комментарий, если нужно
	нажать *create pull request*
	далее *Merge pull request - Confirm merge*
10. Синхронизировать Внешнюю и Локальную ветки Main
	*git pull*
