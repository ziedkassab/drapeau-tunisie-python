# drapeau-tunisie-python
from turtle import *
hideturtle() #Cacher le pointeur de la tortue

#Création du Rectangle
up() #relever le crayon
goto(-200,-100) #déplacer le pointeur
down() #Abaisser le crayon
color('red')
width(5)
begin_fill()
i=0
while i < 2 :
    forward(400)
    left(90)
    forward(300)
    left(90)
    i=i+1
end_fill()

#Cercle 1
up()
goto(0,-45)
pensize(5) #Epaisseur = 5
color('white') #Couleur = 'blanc'
begin_fill()
down()
circle(100) #Cercle de rayon = 80
end_fill()

#Cercle 2
up()
goto(10,-10)
pensize(5) #Epaisseur = 5
color('red') #Couleur = 'rouge'
begin_fill()
down()
circle(60) #Cercle de rayon = 60
end_fill()

up()
goto(30,0)
pensize(5) #Epaisseur = 5
color('white') #Couleur = 'white'
begin_fill()
down()
circle(50) #Cercle de rayon = 50
end_fill()

up()
goto(0,60)
color("red")
pensize(5)
down()
begin_fill()
x = 5
for i in range(x) : #Répétition 5 fois (5 segments d'une étoile
    forward(60) #Avancement d'une distance = 75
    right(144) #Tourner à droite d'angle = 144
end_fill()
