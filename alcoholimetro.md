#Alcoholímetro

##Problemática
Detectar el color en base al alcohol en la sangre de un individuo.  
Existen 4 colores:  
rojo 5.45 o más  
naranja 3.2 a 5.44  
amarillo 2 a 3.2  
verde 0 a 1.9  

##Pseudocódigo
input x  
if (x > = 0 and x < 2)
  print "verde"
    else if (x < = 3.2)
      print "amarillo"
    else if (x < = 5.45)
      print "naranja"
    else if (x > 5.45)
      print "rojo"
Fin
