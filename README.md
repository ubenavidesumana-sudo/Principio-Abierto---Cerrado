# Principio-Abierto---Cerrado
codigos del principio abierto cerrado
la clase Producto guarda lo que tienen en común todos los productos, que es el nombre y el precio. A partir de esta las clases Físico y Digital heredan esos atributos y agregan solo lo que necesitan para cumplir su funcion el peso en el caso del producto físico y la ruta del archivo en el caso de la digital. no tenemos que tocar la clase Producto para incluir esas características nuevas, y si quisiéramos agregar otro tipo de clase podemos crear una nueva clase que herede de Producto

