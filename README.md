# Prettier

### 1. Installiere prettier, prettier-plugin-tailwindcss und prettier-plugin-blade
```
npm install --save-dev prettier-plugin-blade@^2 prettier prettier-plugin-tailwindcss
```

### 2. Kopiere die Prettier Konfigurationsdateien in das Project Verzeichnis
```
cp ~/herd/config-files/.prettierrc ./
cp ~/herd/config-files/.prettierignore ./
```

### 3. PHPStorm einrichten:
**Languages & Frameworks > JavaScript > Prettier**
* Run for Files: `**/*.{js,ts,jsx,tsx,cjs,cts,mjs,mts,vue,astro,blade.php}`
  
**Tools > Actions on Save**
* Run Prettier: Aktivieren
  
