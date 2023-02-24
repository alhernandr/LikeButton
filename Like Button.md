# Like Button

Un boton de like implementable para paginas como redes sociales que al clicarlo rellena el interior del dibujo.

## Uso
Poner 2 imagenes para que cambien al cliquear

## Highlights
```bash
function like(){
    let like = document.getElementById("like");
        if (like.className=='fa-regular fa-thumbs-up icon')
        {
            like.className='fa-solid fa-thumbs-up icon'
        } else {
            like.className = 'fa-regular fa-thumbs-up icon'
        }
    }
```

## Creador

El creador de este diseño es Álvaro Hernández Rodríguez