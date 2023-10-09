# Powershell Bypass 2023

Tener la capacidad de ejecutar scripts en powershell es algo a tener cuenta cuando ganamos acceso a una máquina, en muchas ocasiones se encuentran desactivados por ello, vamos a ver como saltarnos esa configuración sin contar con privilegios ni herramientas automatizadas.

## Que es Powershell

PowerShell es una interfaz de consola con posibilidad de escritura y unión de comandos por medio de instrucciones. Esta interfaz de consola está diseñada para su uso por parte de administradores de sistemas con el propósito de automatizar tareas o realizarlas de forma más controlada.

En este artículo se utilizará un script de prueba llamado test.ps1 que contiene el siguiente código: Write-Host "Código ejecutado"

## Bloqueado? Restringido? Bypass :)

Como se aprecia en la fotografía Powershell se encuentra configurado en modo restringido y prohíbe la ejecución de scripts.

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/3db7444d-780c-42bc-827e-7464b4b1bafb)

### Pegando el código directamente en la consola

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/461bf502-a0c1-447c-93e3-e9932d3ea11b)

### Usando Get-Content o TYPE

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/9cf9f738-e5a3-43b8-ba2f-03983ac7467e)

### Comando

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/f98ba1fe-d2e6-4ce7-ba3b-f80d37ab8920)

### Base64 Encode

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/25da0a18-6260-4a09-8847-0df9044ed8ae)

### Invoke-command

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/ae19dccd-ab5b-4a46-b599-1ed5df0ac989)

### ExecutionPolicy Bypass

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/b300c20d-4c58-4b5e-a075-6ca201d7ce68)

### ExecutionPolicy UnRestricted

![image](https://github.com/ivancabrera02/Powershell/assets/103500562/ce1b65bd-6e01-484f-b65e-eb62765e8964)

