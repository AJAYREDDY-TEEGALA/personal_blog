from django.db import models
from django.contrib.auth.models import User  --important
##from django import forms  ---very important module to take user input and validate and handle 
from django.contrib.auth.decorators import login_required


model --backend data collection point
form -- frontend data collection point



##Resquests:
POST     ---send data through UI (user input the data to server)
GET      ---Get the data (output the data)
PUT      ---update the existing data
DELETE   ---delete the data




every form connects to the database model;
form takes the user input validate and save it into the data model
