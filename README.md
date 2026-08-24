# 🤖 DUbot — Bot Multifunción para WhatsApp

<div align="center">

![DUbot Banner](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/items/master-ball.png)

[![NodeJS](https://img.shields.io/badge/Node.js-v18+-68a063?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Baileys](https://img.shields.io/badge/Baileys-@whiskeysockets-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://github.com/WhiskeySockets/Baileys)
[![Gemini](https://img.shields.io/badge/Google_Gemini-IA_Core-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![Version](https://img.shields.io/badge/Version-1.1.0-orange?style=for-the-badge)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

<p align="center">
  <b>Un bot potente, modular y completo para WhatsApp con economía, juegos de casino, sub-bots Jadibots, IA Gemini, multimedia y salas de inter-chat virtual.</b>
</p>

[🌐 Ver Sitio Web Oficial](https://wa.me/56985529966?text=Hola%20Chile%20Pesos%2C%20quiero%20conseguir%20el%20bot%20DUbot%20para%20mi%20WhatsApp) • [⚡ Conseguir Bot por WhatsApp](https://wa.me/56985529966?text=Hola%20Chile%20Pesos%2C%20quiero%20conseguir%20el%20bot%20DUbot%20para%20mi%20WhatsApp) • [📋 Lista de Comandos](#-comandos-principales)

</div>

---

## 🌟 Características Destacadas

### 🤖 1. Sistema Jadibot (Sub-Bots Independientes)
* Convierte cualquier número de WhatsApp en un **sub-bot activo** en segundos.
* Vinculación rápida mediante **código de 8 dígitos** o **código QR**.
* Asignación automática de prefijo personalizado por sub-bot (`a.`, `b.`, `c.`, etc.).
* Sistema de **prioridad de usuario** y confirmación inteligente contra spam.
* Persistencia de sesión tras reinicios del servidor.

### 💰 2. Economía Completa, Banco & Préstamos
* Moneda virtual (`$`) con bóveda bancaria e intereses diarios.
* Trabajos con recompensas progresivas (`.work`, `.daily`, `.weekly`, `.monthly`).
* Préstamos bancarios con interés y plazos de vencimiento (`.prestamo`, `.deuda`, `.pagardeuda`).
* Sistema de robos entre usuarios (`.rob`) con probabilidad de ser arrestado y multas.
* Ranking global de los usuarios más ricos (`.top`).

### ⛏️ 3. Minería, Pesca, Caza & Crafteo
* Recolección de materiales raros mediante minería, pesca y cacería.
* Sistema de **Forja y Crafteo** (`.crafteo`) para fabricar herramientas (Pico de Diamante, Caña Pro, Armas de Caza).
* Mercado e inventario de ítems interactivo (`.inv`, `.shop`, `.use`).

### 🎰 4. Casino & Minijuegos
* **Blackjack vs Bot** (`.blackjack`) con crupier automático y cálculo de cartas.
* **Ruleta Clásica** (`.roulette rojo/negro`).
* **Tragamonedas / Slots** (`.slots`) y **Dados** (`.dice`).
* **Ruleta Rusa** (`.ruletarusa`) de alto riesgo con multas de cárcel.
* **Lotería Global Acumulativa** (`.loteria`) con pozo millonario.

### 🧠 5. Inteligencia Artificial (Google Gemini)
* Conversaciones fluidas con memoria y contexto de chat (`.ai [pregunta]` o por mención).
* **Generador de Imágenes** integrado (`.ai genera una imagen de [...]`) usando Imagen 4.0.
* **Torneos de Debates con Juez IA** (`.debate`, `.startdebate`, `.apostar`) con puntuaciones y apuestas de espectadores.

### 📡 6. Inter-Chat Virtual (IV)
* Conexión privada 1 a 1 entre usuarios de distintos grupos (`.iv conectar @user`).
* **Salas Virtuales con Código** (`.iv crear [nombre]`, `.iv unirse [código]`) para chatear entre múltiples chats en tiempo real.

### 🔍 7. Búsquedas Multiplataforma & Multimedia
* Stickers de alta calidad conservando el **aspecto original** (`.sticker`, `.s`).
* Descarga de música en MP3 directamente desde YouTube (`.play`).
* Búsquedas con enlaces directos en **TikTok** (`.tiktok`), **Instagram** (`.ig`), **Pinterest** (`.pin`), **Google** (`.google`) y **Spotify** (`.spotify`).
* Generador de códigos QR (`.qr`).

### 🕒 8. Detección de Hora Local y Mundial
* Comando inteligente (`.hora`) que detecta tu país y zona horaria a partir del prefijo telefónico (+56 Chile, +52 México, +54 Argentina, +57 Colombia, +34 España, etc.).
* Compatible con cuentas con privacidad `@lid`.

### 💡 9. Corrector Inteligente de Comandos
* Si cometes un error de tipeo (ej: `.mennu`, `.worrk`), el bot calcula la distancia de Levenshtein y te sugiere el comando correcto automáticamente.

---

## 📋 Comandos Principales

| Categoría | Comando | Aliases | Descripción |
| :--- | :--- | :--- | :--- |
| **Economía** | `.work` | `.w`, `.trabajar` | Trabajar para ganar dinero y XP |
| **Economía** | `.daily` | `.diario` | Reclamar tu recompensa diaria |
| **Economía** | `.bal` | `.balance`, `.banco` | Ver tu dinero en mano y en el banco |
| **Economía** | `.dep [monto/all]` | `.depositar` | Depositar dinero en tu cuenta bancaria |
| **Economía** | `.with [monto/all]`| `.retirar` | Retirar dinero del banco |
| **Economía** | `.pay [@user] [monto]` | `.p`, `.transferir` | Transferir dinero a otro usuario |
| **Economía** | `.rob [@user]` | `.r`, `.robar` | Intentar robar dinero a un usuario |
| **Economía** | `.top` | `.lb`, `.ricos` | Ranking de los usuarios con más dinero |
| **Economía** | `.prestamo [monto]`| `.pedirprestamo`| Pedir un préstamo al banco con interés |
| **Trabajos** | `.minar` | `.mina` | Minar minerales valiosos |
| **Trabajos** | `.pescar` | `.pesca` | Pescar peces y tesoros |
| **Trabajos** | `.cazar` | `.caza` | Cazar criaturas salvajes |
| **Trabajos** | `.crafteo` | `.craft`, `.forja`| Ver recetas y craftear herramientas |
| **Casino** | `.blackjack [monto]` | `.bj` | Jugar Blackjack contra el bot |
| **Casino** | `.roulette [color] [monto]` | `.rl` | Apostar a la ruleta (rojo/negro) |
| **Casino** | `.slots [monto]` | `.sl` | Tragamonedas clásico |
| **Casino** | `.dice [monto]` | `.dc` | Apostar a los dados |
| **Casino** | `.ruletarusa [monto]` | `.rr` | Ruleta rusa de alto riesgo |
| **Casino** | `.loteria comprar` | `.lotto` | Comprar boletos para la lotería |
| **IA** | `.ai [mensaje]` | `.gemini`, `.bot` | Chatear con Google Gemini IA |
| **IA** | `.debate` | `.torneo` | Crear torneo de debate juzgado por IA |
| **Jadibot** | `.jadibot` | `.subbot`, `.code`| Vincular tu número como un sub-bot |
| **Jadibot** | `.stopjadibot` | `.detenerbot` | Apagar tu sub-bot activo |
| **Jadibot** | `.subbots` | `.jadibots` | Ver lista de sub-bots conectados |
| **Inter-Chat** | `.iv conectar @user`| `.interchat` | Conectar llamada privada 1 a 1 |
| **Inter-Chat** | `.iv crear [nombre]`| `.iv` | Crear sala virtual para grupos |
| **Búsqueda** | `.tiktok [texto]` | `.tt`, `.tiktoksearch` | Buscar videos en TikTok |
| **Búsqueda** | `.instagram [texto]`| `.ig`, `.instasearch` | Buscar perfiles y temas en Instagram |
| **Búsqueda** | `.pinterest [texto]`| `.pin`, `.pinsearch` | Buscar ideas e imágenes en Pinterest |
| **Búsqueda** | `.google [texto]` | `.buscar`, `.gsearch` | Buscar en Google / Web |
| **Búsqueda** | `.spotify [canción]` | `.sp`, `.spotsearch` | Buscar música en Spotify |
| **Multimedia**| `.sticker` | `.s`, `.stiker` | Convertir imagen/video a sticker |
| **Multimedia**| `.play [canción]` | `.ytmp3`, `.mp3` | Descargar canción en audio MP3 |
| **Utilidad** | `.hora [país]` | `.time`, `.reloj` | Ver hora local de tu país o mundial |
| **Utilidad** | `.qr [texto/url]` | `.qrcode` | Generar código QR escaneable |
| **Utilidad** | `.owner` | `.creador`, `.dev` | Información oficial del creador |

---

## 🚀 Instalación y Despliegue Local

### 1. Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/mi_bot.git
cd mi_bot
```

### 2. Instalar dependencias
```bash
npm install
```

### 3. Configurar API Key de Gemini
Obtén tu clave gratuita en [Google AI Studio](https://aistudio.google.com/) y configúrala como variable de entorno o ingrésala al iniciar el bot:
```bash
# En Windows (PowerShell)
$env:GEMINI_API_KEY="tu_api_key_aqui"

# En Linux / MacOS
export GEMINI_API_KEY="tu_api_key_aqui"
```

### 4. Iniciar el bot
```bash
node bot.js
```

1. Elige tu método de vinculación preferido:
   * **1. Código QR:** Escanea el código con WhatsApp.
   * **2. Código de 8 dígitos:** Ingresa tu número de teléfono y escribe el código en WhatsApp > *Dispositivos vinculados*.

---

## 👑 Información del Creador

<div align="center">

| Creador | WhatsApp User | Plataforma | Lenguaje | Contacto |
| :--- | :--- | :--- | :--- | :--- |
| **Chile Pesos** | **@doodle duo** | **PC** | **Node.js (Baileys)** | [📲 +56 9 8552 9966](https://wa.me/56985529966) |

[![Contactar por WhatsApp](https://img.shields.io/badge/Contactar_al_Creador-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/56985529966?text=Hola%20Chile%20Pesos%2C%20quiero%20conseguir%20el%20bot%20DUbot%20para%20mi%20WhatsApp)

</div>

---

## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.

---

<div align="center">
  <sub>Desarrollado con ❤️ y dedicación por <b>Chile Pesos (@doodle duo)</b>.</sub>
</div>
