# UE4rpgRole_2016

Videojuego de Unreal Engine 4 del tipo rpg.

# Historia:

La idea es conquistar territorio enemigo en modo multijugador o de un juagdor. Existen tres tipos de personajes: Guerrero, Cazador y Mago en dos bandos distintos. [Por continuar]

# Tarea 1.[inicializar proyecto] Fecha:12/08/2016

## Inicializar proyecto
# Crear interfaz de usuario:
1.*Menú principal
    1. *Un Jagador
        1. *Campaña
        2. *Batalla
2.*Multijugador
    1. *Lan
    2. *Internet
3.*Ajustes
    1. * Video
    2. * Sonido
    3. * Modo de juego
# Raiz del proyecto:

1.Content [dir]
    1.Raiz [dir]
        1. funcionesU [dir]
            1. interfaces [blupirnts fn> fn U]
        2. menuPrincipal [dir]
            1.menuPrincipal [widget]
            2.unJugador [widget]
            3.sistemaInterfaces [actor]
            4.Ajustes [widget]
            5.Ajustes video [widget]
            6.Ajustes audio [widget]
            7.Ajustes modo de juego [widget]
        3.objetos [dir]
            1.btnLink [widget]
            2.btnLink-Campaña [btnLink]
        4.savegames [dir]
        5.estructuras [dir]
            1.savegame [estructura]
        1.Savegames

Estructura de savegame en raiz/estructuras
Savegames almacenados en objetos/savegames