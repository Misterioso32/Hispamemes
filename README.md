# hispamemes
Npm muy simple dedicado a generar imagenes/videos de memes de la comunidad hispanohablante
actualmente el npm con mas memes de los npms de la comunidad hispana

+250 Memes diferentes en formato imagen en español

Proximamente video memes

(Objectivo llegar a +1000 memes diferentes)

si encuentras algun error no dudes en reportarlo o al gmail o al dm de discord Misterioso32#4542
## Instalación
```sh
npm i hispamemes
```
## Uso
```js
const hispamemes = require("hispamemes");
const meme = hispamemes.meme();
```
## Ejemplo
```js
const hispamemes = require("hispamemes");
const meme = hispamemes.meme();

const embed = new Discord.MessageEmbed()
  .setTitle("Meme Imagen")
  .setColor("BLUE")
  .setImage(meme)
  .setFooter({text: `Meme pedido por ${message.member.displayName}`})
  .setTimestamp()
  
message.channel.send({ embeds: [embed] })
```
## Advertencias
- Algunos memes pueden ser ofesivos para algunas personas o colectivos
- Algunos de los memes contiene referencias +18
- Ninguna de las imagenes de los memes tiene contenido NSFW