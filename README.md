
# Tutorial Como Obtener El Tono de Llamada Secreto de Discord


> C贸digo del tutorial de [Como Obtener El Tono de Llamada Secreto de Discord](https://google.com)
## Requisitos

1. Tener una cuenta de Discord
2. Tener la versi贸n de Discord WEB o Discord Desktop (Stable, PTB o Canary)

## 馃殌 C贸digo del v铆deo

```js
Audio.prototype._play = Audio.prototype.play;
Audio.prototype.play = function() {
    this.src = this.src.replace(/84a1b4e11d634dbfa1e5dd97a96de3ad/g, 'b9411af07f154a6fef543e7e442e4da9');
    return this._play();
};
```

## Pasos
1. Copiar el c贸digo
2. Ir a Discord
3. Presionar CTRL + SHIFT + I o CTRL + MAY脷S + I
4. Abrir el apartado "Console" o "Consola"
5. Pegar el c贸digo copiado anteriormente
6. Darle a enter
7. Esperar a que alguien te llame


## 馃摑 Cr茅ditos
* [DISCORD](https://discord.gg/tecnobros)
* [YOUTUBE](https://youtube.com/tecnobros)

Copyright 漏 **1ly4s0#2477** - 2023
