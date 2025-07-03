# Sistema Gestor de Ventas y Alquiler de Peliculas

Descripción breve del proyecto, su propósito y características principales.

## Tabla de Contenidos
- [Instalación](#instalación)
- [Comandos](#comandos)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Instalación

Instrucciones para instalar:

```bash
# Crear el proyecto
ng new app-movie-shop-lq --routing --style=scss
```

## Comandos

Estructura del Proyecto y Comando

```bash
# Servicios
ng g s core/services/firestore --skip-tests
ng g s core/services/auth --skip-tests
```
```bash
# Componentes
ng g c layout/header --skip-tests
ng g c layout/navbar --skip-tests
ng g c layout/footer --skip-tests
```
```bash
# Interfaces
 ng g i core/interfaces/usuario --type=model
 ng g i core/interfaces/pelicula --type=model 
 ng g i core/interfaces/orden --type=model
 ng g i core/interfaces/prestamo --type=model
```

# Instalación de Dependencias y Librerias:
 
```bash
# Instalar Tailwind
npm install tailwindcss @tailwindcss/postcss postcss --save
```
**Nota:**  Crear un archivo en la raiz ".postcssrc.json" y pega el siguiente codigo
```
{
  "plugins": {
    "@tailwindcss/postcss": {}
  }
}

```

```bash
# Instalr flowbite
npm install flowbite --save

```
