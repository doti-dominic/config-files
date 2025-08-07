# Persönliche Sammlung von Config-Files

Primär für die Laravel Entwicklung.
👉 Installieren, Kopieren, Fertig 🎉 

## Inhalt

- [Prettier](#Prettier)

---

# Prettier

*Quellen: [Prettier.io](http://prettier.io) | [MattStauffer.com](https://mattstauffer.com/blog/how-to-set-up-prettier-on-a-laravel-app-to-lint-tailwind-class-order-and-more/)*

## ⬇️ 1. Installiere prettier, prettier-plugin-tailwindcss und prettier-plugin-blade

```sh
npm install --save-dev prettier-plugin-blade@^2 prettier prettier-plugin-tailwindcss
```

## 🚚 2. Kopiere die Prettier Konfigurationsdateien in das Projektverzeichnis

```sh
cp ~/herd/config-files/.prettierrc ./
cp ~/herd/config-files/.prettierignore ./
```

> 🎛️ PHPStorm
> 
> - Languages & Frameworks > JavaScript > Prettier
>   
> `Run for Files: **/*.{js,ts,jsx,tsx,cjs,cts,mjs,mts,vue,astro,blade.php}` (`blade.php` hinzufügen)
> 
> - Tools > Actions on Save
>   
> `Run Prettier: ✅` (Aktivieren)
