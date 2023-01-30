## Marvel_Auth
Alternate login mechanism based on grids instead of normal alpha-numeric mechanism. It will sort out the problems raised due to long complexity 
difficult passwords and easy to crack short passwords. 

## Security principles

### Bruteforcing
> Bruteforcing cannot be possible in this login mechanism. Dictionary based attacks and common password attacks can't be suuported over here. Every
time when a user login it will ask to select the grids that the user set as a password during the registration process.

### Shoulder surfing
> Shoulder surfing refers to see what does the user types as a password during login/registartion process. In this login mechanism the selection of
grids was minimized so it is difficult to estimate the selection of grids for the attacker.

[For installing django in your machine follow these steps](https://docs.djangoproject.com/en/4.1/topics/install/)

## Configuration 
```
gh repo clone dharneesh013/Marvel_Auth
cd Marvel_Auth
python3 manage.py createsuperuser
python3 manage.py runserver localhost:8000
```

## Result

![login](https://user-images.githubusercontent.com/77725682/209757952-004e9d6a-2ae0-4105-b928-b3871d03c3f0.jpg)


