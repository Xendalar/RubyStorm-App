# ⚡ Ruby Storm — MTG Game Assistant
¡Hola!
Soy Xendalar, Alfredo para los que me conocen.

Cuando empecé a jugar Ruby Storm vi un problema: llevar la cuenta de las cosas con dados es un enorme peñazo porque en cualquier momento les das un golpe y 
ahora vete tú a saber por cuánto iba la cuenta. Normalmente no es tan complicado, pero puede pasar que no haya acuerdo o que simplemente los jugadores no recuerden.
Llevar las cuentas a papel es otra opción y más segura, pero a veces no quieres cargar con un libreta y boli o te da pereza y ya está.

Pues ea, para eso hice esta app. Llevo poco programando pero si tienes la capacidad, ¿por qué no? Igual que si eres panadero no vas a comprarle el pan al de al lado (o sí, no me meto en la vida interna de los panaderos),
pues siendo programador si tienes un problema que se puede resolver con una app, lo más cómodo es sentarte y hacerla a tu medida. Como no había nada similar, o no he encontrado nada similar, aquí estamos. 

## Description

A mobile web app (PWA) designed as a game assistant for the **Ruby Storm** deck in Magic: The Gathering's **Modern** format.

Available in **Spanish and English**.

---

## Features

- **Ral coin flip** — tap to flip and track heads/tails streaks
- **Storm Count** — separate counters for Storm (all spells, for Grapeshot) and Ral (instants/sorceries only, for his loyalty)
- **Mana tracker** — red mana by default, add any of the five colors as needed
- Installable as a home screen app on Android and iOS (no app store needed)

---

## How to install

### Android (Chrome)

1. Open the app link in **Chrome**
2. Tap the **three-dot menu** (top right)
3. Select **"Add to Home screen"**
4. Confirm by tapping **"Add"**

The app will appear on your home screen and open full-screen, just like a native app.

### iOS (Safari)

1. Open the app link in **Safari**
2. Tap the **Share button** (square with arrow icon, bottom bar)
3. Select **"Add to Home Screen"**
4. Confirm by tapping **"Add"**

> Chrome on iOS does not support PWA installation. Use Safari.

---

## Self-hosting (GitHub Pages)

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. GitHub will give you a URL like `https://yourusername.github.io/ruby-storm`
5. Share that link and users can install the app from it

---

## Files

| File | Description |
|---|---|
| `index.html` | Main app |
| `manifest.json` | PWA manifest (name, icons, colors) |
| `sw.js` | Service worker (offline support) |
| `icons/` | App icons in multiple sizes |

---

## Support

If you find this useful, you can support development on [Ko-fi](https://ko-fi.com/xendalar).

---

*Not affiliated with Wizards of the Coast. Magic: The Gathering is property of Wizards of the Coast LLC.*
