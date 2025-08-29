# Mis Apuntes de _P.L.I_

## Comandos básicos de terminal

## Sintaxis de _Markdowm_

## Comandos de _Git_ 

### Configuración Inicial 

Estos comandos los vas a ejecutar una sola vez, depúes de que hayas instalado _**Git**_ en tu computadora 

```bash
git --version
git config --global user.name "Jonathan MirCha"
git config --global user.email jonmircha@gmail.com
git config --global user.ui true
git config --global init.defaultBranch main
git config --list
# asignando visual studio code como editor de configuración de git
git config --global core.editor "code --wait"
git config --global -e
# para estandarizar los saltos de línea en windows
git config --global core.autocrlf true
# para estandarizar los saltos de línea en linux/mac
git config --global core.autocrlf input
# ver todas las opciones de la configuración en la terminal
git config -h
# ver todas las opciones de la configuración en el navegador
git help config
```

### Inicializando _Git_

Este comando lo debemos ejecutar sólo una vez, para indicarle a _git_ que comience a darle seguimiento al contenido de nuestra carpeta

El siguiente comando nos ayuda a visualizar el estado de seguimiento de nuestra carpeta

![Flujo básico de Git y Git Hub](https://jonmircha.com/img/blog/git-flow.png)

# Encabezado Nivel 1

## Encabezado Nivel 2

### Encabezado Nivel 3

#### Encabezado nivel 4

##### Encabezado nivel 5

###### Encabezado nivel 6

```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }

  let c = a + b;
  return c;
}
```

<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q" required />
  <input type="submit" value="🔍" />
</form>

Esto es un párrafo, el párrafo en markdown se cierra cuando damos enter 

Esto es otro párrafo

Para poner **negritas** debes encerrar la palabra entre doble asterisco

Para poner _cursiva_ debes encerrar el texto entre guiones bajos

Para poner _**cursiva y negritas**_ debes encerrar el texto entre guiones bajos y asteriscos 

- Primavera
- Verano
- Otoño
- Invierno 

1. Primavera
1. Verano
1. Otoño
1. Invierno

| País | Ciudad | Continente
| - | - | - |
| México | CDMX | América | 
| Francia | París | Europa |
| Japón | Tokio | Asía |


![This is JavaScript!!!!](https://static.wixstatic.com/media/a81c9f_1d65d333c4404a23a05969f48cc95bf8~mv2.jpeg/v1/fill/w_568,h_1010,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/a81c9f_1d65d333c4404a23a05969f48cc95bf8~mv2.jpeg)

[Visita la web de Amerike](https://amerike.edu.mx/)

[Aprende la sintaxis](https://jonmircha.com/markdown)

> Yo solo sé que no sé nada 

<!-- Esto es un comentario en MarkDown -->