# Diccionario-Python
# Crear el diccionario con información ficticia
informacion_personal = {
    "nombre": "Carlos Pérez",
    "edad": 30,
    "ciudad": "Quito",
    "profesion": "Ingeniero"
}

# Acceder y modificar el valor de "ciudad"
informacion_personal["ciudad"] = "Guayaquil"

# Agregar una nueva clave-valor (ya existe "profesion", pero agregaremos otro valor opcionalmente)
informacion_personal["ocupacion"] = "Desarrollador de software"

# Verificar si la clave "telefono" existe, si no, agregarla
if "telefono" not in informacion_personal:
    informacion_personal["telefono"] = "0987654321"

# Eliminar la clave "edad"
del informacion_personal["edad"]

# Imprimir el diccionario final
print(informacion_personal)
