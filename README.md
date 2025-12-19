# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Car Inventory Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
from django.db import models
from django.contrib import admin
# Create your models here.
class Car(models.Model):
    regno=models.CharField(max_length=20,help_text="Register Number")
    name=models.CharField(max_length=100)
    price=models.IntegerField()
    year=models.IntegerField()
class CarAdmin(admin.ModelAdmin):
    list_display=('regno','name','price','year')
```

## OUTPUT
<img width="1293" height="723" alt="image" src="https://github.com/user-attachments/assets/a7f30934-2444-4027-a178-4732e0806f2e" />


## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
