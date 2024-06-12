# DiazBot-v3
> <b>🚀 VERSIÓN 3.0</b>

<p align="center"> 
<a href="https://github.com/Diaz1975"><img src="http://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=B1F733&width=435&lines=DiazBot-v3;Disfruta+del+bot.+%E2%9A%A1" height="90px"></a> 
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">

<p align="center">
<img src="https://telegra.ph/file/86afc8b4881e2013cded4.jpg" alt="KatashiBot-MD" width="900"/>
</p>

> 𝑴𝑼𝑪𝑯𝑨𝑺 𝑮𝑹𝑨𝑪𝑰𝑨𝑺 𝑷𝑶𝑹 𝑷𝑹𝑬𝑭𝑬𝑹𝑰𝑹𝑵𝑶𝑺 😎✨
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">

<p align="center">
<a href="#"><img title="DiazBot-v3" src="https://img.shields.io/badge/SI TE AGRADA EL REPOSITORIO APÓYAME CON UNA 🌟 ¡GRACIAS! -red?colorA=%255ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>  

<p align="center">
<a href="#"><img title="DiazBot-v3" src="https://img.shields.io/badge/COMPATIBLE CON LA VERSIÓN MULTI DISPOSITIVOS DE WHATSAPP-red?colorA=%F77F48FF&colorB=%F77F48FF&style=for-the-badge"></a>
</p>

<p align="center">   
<a href="https://github.com/KatashiFukushima/KatashiBot-MD/network/members"><img title="Forks" src="https://img.shields.io/github/forks/KatashiFukushima/KatashiBot-MD?label=Forks&color=blue&style=flat-square"></a>
<a href="https://github.com/KatashiFukushima/KatashiBot-MD/watchers"><img title="Watchers" src="https://img.shields.io/github/watchers/KatashiFukushima/KatashiBot-MD?label=Watchers&color=green&style=flat-square"></a>
<a href="https://github.com/KatashiFukushima/KatashiBot-MD/stargazers"><img title="Stars" src="https://img.shields.io/github/stars/KatashiFukushima/KatashiBot-MD?label=Stars&color=yellow&style=flat-square"></a>
</p>

### Cuentas Oficiales:
> Al acceder a la plataforma, obtendrás acceso a todos los enlaces oficiales de Katashi Fukushima. Además, te mantendremos informado con boletines y mensajes exclusivos sobre las últimas novedades. La página se actualiza constantemente para ofrecerte la información más relevante. ¡No te pierdas ninguna actualización y únete a nuestro canal ahora mismo!

<a href="https://www.atom.bio/katashifukushima">
<img src="https://img.shields.io/badge/Redes_Sociales-000000%7D?style=for-the-badge&logo=biolink&logoColor=white">
</a>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">

### 🌟 (OPCIÓN 1) INSTALACIÓN AUTOMÁTICA POR TERMUX 🫰
[![blog](https://img.shields.io/badge/Instalacion-Automatica-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/shorts/ZLJYDUM6vSY)
> **Note** Comandos para instalar de forma automática en Termux  
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget mpv && wget -O - https://raw.githubusercontent.com/diaz1975/DiazBot-v3/master/katashi.sh | bash
```
```js
// PERSONALIZAR INSTALACIÓN AUTOMÁTICA (En caso de una Bifurcación)
// Parámetros editables

// REFERENCIA
"wget -O - https://raw.githubusercontent.com/KatashiFukushima/KatashiBot-MD/master/katashi.sh | bash"

// PARÁMETROS QUE PUEDE SER MODIFICADOS --> "[...]"
"wget -O - https://raw.githubusercontent.com/[usuario]/[repositorio]/[rama]/katashi.sh | bash"
```
#### MODIFICAR ARCHIVO [`katashi.sh`](https://github.com/KatashiFukushima/KatashiBot-MD/blob/master/kata.sh)
```js
//LÍNEAS A MODIFICAR
205 --> "git clone https://github.com/[user]/[repositorio].git"
//Ejemplo: git clone https://github.com/KatashiFukushima/KatashiBot-MD.git

209 --> "cd [repositorio]"
//Ejemplo: cd KatashiBot-MD

//Una vez hecho estos cambios ejecute los nuevos comandos en Termux
```

### 🚀 USAR DIAZBOT 24/7 EN TERMUX 
> Ejecutar estos comandos dentro de la carpeta KatashiBot-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 
#### ⬇️ Opciones Disponibles
> **Warning** Esto eliminará todo el historial que hayas establecido con PM2:
```bash 
pm2 delete index
``` 
> Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:
```bash 
pm2 logs 
``` 
> Si desea detener la ejecución de Termux use:
```bash 
pm2 stop index
``` 
> Si desea iniciar de nuevo la ejecución de Termux use:
```bash 
pm2 start index
``` 
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">
  
### 🥷🏻 ACTUALIZAR DIAZBOT
> **Note** Comandos para actualizar KatashiBot-MD de forma automática
```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget && wget -O - https://raw.githubusercontent.com/diaz1975/DiazBot-Prueba4/master/update.sh | bash 
```
#### Para que no pierda su progreso en KatashiBot, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> **Warning** Estos comandos solo funcionan para TERMUX, REPLIT, LINUX                           
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">

  
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">
  
### 💠 [`IDIOMAS DISPONIBLES PARA DIAZBOT`](https://github.com/Diaz1975/DiazBot-v3/blob/master/config.js) 
#### 🌐 Español  
#### 🌐 Inglés (English) 
#### 🌐 Portugués (Português)
#### 🌐 Indonesio (Bahasa Indonesia) 
#### 🌐 Árabe (عرب)
#### 🌐 Hindi (Indian Language)
- [x] Ejemplo <details><summary>Idioma</summary><img src="https://i.imgur.com/ZTwOGkT.jpg"></details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br><br>
<p align="center">

### 🌟 AGRADECIMIENTOS
[![TheShadowBrokers1](https://github.com/GataNina-Li.png?size=60)](https://github.com/GataNina-Li) 

### 🌟 CREADOR 
DÍAZ MOD
> Copyright (c) 2024 **[DiazMod](https://github.com/diaz1975/DiazBot-v3/blob/master/LICENSE)**.
