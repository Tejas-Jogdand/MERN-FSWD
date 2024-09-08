## How to setup Tailwind css

step 1: Run 
```
npm install -D tailwindcss   
```
```
npx tailwindcss init
```

step 2 : Update tailwind.config.js to include this
```
content:["*.html"]
```

step3: Create src/input.css and include
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

step 4: Include src/output.css in html

step 5: Run the following  command
```
npx tailwindcss -i src/input.css -o src/output.css
```