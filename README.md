# Swartz-7 TailwindCSS + Vite Template

This is a template to use for a `html` + `vanillajs` + `tailwindcss` project. Enjoy. Make it better.

<br/>

<p align="center">
  <a href="https://tailwindcss.com" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg">
      <img alt="Tailwind CSS" src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg" width="350" height="70" style="max-width: 100%;">
    </picture>
  </a>
</p>

<br />

## Documentation 📄

Les libraries principales utilisé sont:

1. [tailwindcss](https://tailwindcss.com/)
2. [vite](https://vitejs.dev/)

## ⚠️ Requis 🚨

Il est obligatoire d'avoir [Node](https://nodejs.org/en/download/)
installé.

Au moins `node >= 14.18.0`.

Si tu veux installer plusieurs versions de node dans ton systeme. Regarde `nvm` (node version manager) ou qql similaire

## Utilisation 🥹

1. `git clone <address de ce template> <my-renamed-folder>` le project
2. `cd <my-renamed-folder>`
3. Installe les dépendances nécessaires avec `npm install`

_Note: en lieu d'tuliser `npm` tu peux utiliser `yarn` comment 'dependence manager'. [Montre moi comment utiliser Yarn](#Yarn)._

## Développement 🏋️

- `npm run dev` lance un serveur de dév local qui recharge automatiquement les scripts et le front-end avec
- Pour te faciliter la vie avec les classes du `tailwindcss` installe cette [extension](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) sur vscode.

## Production 👔

- `npm run build` cree un build "production" du projet dans le dossier `dist`

- `npm run serve` fais un preview du **build production**

## Yarn 🧶

Si tu utlise [yarn](https://yarnpkg.com/) comme package manager.

1. Installe `yarn` dans ton OS.
2. Retire le `package-lock.json` du projet
3. En lieu de faire `npm install` fais `yarn install` pour installer les dependances avec `yarn`
4. Utilise `yarn` pour toute commande `yarn run dev || yarn run build || yarn add pkg || ...etc`

## Contribute

... Add some info

## TODO

- [ ] Installe + Configurer prettier + tailwind plugin pour faciliter l'ordre de tailwindcss.classes. Read about it [here](https://tailwindcss.com/docs/editor-setup#automatic-class-sorting-with-prettier).
- [ ] ADD MIT License.
- [ ] Configure template to use `typescript`.
- [ ] Create executable to allow me to choose between using `yarn` or `npm`

---

&copy; 2022
