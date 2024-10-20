# Angel-Alejandro-Sepulveda-Gonzalez-3W-1215-pr1

# Angel Alejandro Sepulveda Gonzalez, 3W, 1215

# Crear un diccionario con campos predefinidos para almacenar la información de la persona

persona = {

  "edad": None,
    
  "sexo": None,
    
  "género": None,
    
  "número de celular": None,
  
  "dirección": None

}

# Función para pedir datos y añadirlos al diccionario

def agregar_informacion():

  # Recorrer cada clave del diccionario y pedir el valor correspondiente
 
  for clave in persona:
        
  # Pedir al usuario que introduzca el valor para cada clave
  
  valor = input(f"Introduce el/la {clave}: ")
        
  # Añadir el valor al diccionario
  
  persona[clave] = valor
        
  # Imprimir el contenido actualizado del diccionario
        
  print("Datos actuales:", persona)

# Ejecutar la función para comenzar a pedir la información

agregar_informacion()

![image](https://github.com/user-attachments/assets/30071c6c-2f3c-4b08-be13-3049fff32604)
![image](https://github.com/user-attachments/assets/265e79d4-a758-4e73-88b7-25689a15d23b)
![image](https://github.com/user-attachments/assets/73971fcb-a6b2-4b4d-99e6-39273a6b7602)


