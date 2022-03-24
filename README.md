# Gamification
To update DB models:
```
python manage.py inspectdb > achievements\\models\\DBmodels.py
(Get-Content .\achievements\models\DBmodels.py) -replace '\0' -ne '' | Set-Content .\achievements\models\DBmodels.py
```
