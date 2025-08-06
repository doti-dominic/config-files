# Prettier

## 1. Install prettier, prettier-plugin-tailwindcss, and prettier-plugin-blade with npm install 
```
npm install --save-dev prettier-plugin-blade@^2 prettier prettier-plugin-tailwindcss
```

## 2. Add [.prettierrc](.prettierrc) and [.prettierignore](.prettierignore) file to your project root
```
cp ~/herd/config-files/.prettierrc ./
cp ~/herd-config-files/.prettierignore ./
```

## 3. Setup PHPStorm:
**Languages & Frameworks > JavaScript > Prettier**
* Run for Files: `**/*.{js,ts,jsx,tsx,cjs,cts,mjs,mts,vue,astro,blade.php}`
