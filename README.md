# Diccionario para almacenar nombres de usuario y contraseñas
usuarios = {'usuario1': 'contraseña1', 'usuario2': 'contraseña2', 'usuario3': 'contraseña3'}

def login():
    usuario = input("mneyzberg@comcast.net: ")
    contraseña = input("Kat4rine722: ")

    # Verificar si el nombre de usuario está en el diccionario y si la contraseña coincide
    if usuario in usuarios and usuarios[usuario] == contraseña:
        print("¡Inicio de sesión exitoso!")
    else:
        print("Nombre de usuario o contraseña incorrectos. Inténtelo de nuevo.")

# Ejecutar la función login
login(generador.py)
