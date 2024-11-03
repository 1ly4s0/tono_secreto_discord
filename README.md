
# Tutorial Como Obtener El Tono de Llamada Secreto de Discord


> Código del tutorial de [Como Obtener El Tono de Llamada Secreto de Discord](https://youtu.be/7cXMGNv5mfA)
## Requisitos

1. Tener una cuenta de Discord
2. Tener la versión de Discord WEB o Discord Desktop (Stable, PTB o Canary)

## 🚀 Código del vídeo

```js
Audio.prototype._play = Audio.prototype.play;
Audio.prototype.play = function() {
    this.src = this.src.replace(/84a1b4e11d634dbfa1e5dd97a96de3ad/g, 'b9411af07f154a6fef543e7e442e4da9');
    return this._play();
};
```

## Pasos
1. Copiar el código
2. Ir a Discord
3. Presionar CTRL + SHIFT + I o CTRL + MAYÚS + I
4. Abrir el apartado "Console" o "Consola"
5. Pegar el código copiado anteriormente
6. Darle a enter
7. Esperar a que alguien te llame


## 📝 Créditos
* [DISCORD](https://discord.gg/tecnobros)
* [YOUTUBE](https://youtube.com/tecnobros)

Copyright © **1ly4s0#2477** - 2023
