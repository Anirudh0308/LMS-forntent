# React + Vite

# LMS Frontend

### Setup instruction

1. clone the project
``` 
    git clone https://github.com/Anirudh0308/lms-frontend.git
```
2. move into directory
``` 
    cd lms-frontend 
```
3. install dependencies
``` 
    npm i
```
4. run the server
```
    npm run dev
```
####  Setup instruction for tailwind css  ####

[tailwindcss installation doc link ]https://tailwindcss.com/docs/installation/using-vite
1. install installation
```
    npm install -D tailwindcss@3
```
2. Create tailwind config file
```
    npx tailwindcss init
```
3. Add file extention to tailwind config file in the contents property
    "./src/**/*.{html,js}"
    "./src/**/*.{html,js,jsx,ts,tsx}"

4. Add the tailwind directives at the top of the end 'index.css' file
    ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

5. Add  link tag in index.html file under head tag
```
    <link href="./output.css" rel="stylesheet">
```

### install dependencies :- 
 npm install @reduxjs/toolkit react-redux react-router-dom react-icon react-chartjs-2 chart.js daisyui axios react-hot-toast 
 npm i @tailwindcss/line-clamp

### eslint cofiguration :
1. install
```
    npm i -D eslint-plugin-simple-import-sort
```
2. Add rule in `.eslint.cjs`
```
    'simple-import-sort/imports': 'error'
```
3. Add simple-import sort plugin in `.eslint.cjs`
```
    plugins:[.... , 'simple-import-sort']
```
4. To enable auto import sort on file save in vscode
    -open `settings.json`
    -add the following config
```
    "editor.codeActionsOnSave":{
        "source.fixAll.eslint":true
    }
```
