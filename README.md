
# Angular 13 with Tailwindcss

If you want to create a new project just do the following steps.

    1. ng new <project-name>
    2. npm install -D tailwindcss postcss@latest autoprefixer@latest
    3. npx tailwindcss init
    4. paste this into the tailwind.config.js 

>     module.exports = {
>         content: ["./src/**/*.{html,ts}"],
>         theme: {
>         extend: {},
>     },
>     plugins: [],
>     };
    5. If your using CSS copy & paste this into your styles.css
>         @tailwind base;
>         @tailwind components;
>         @tailwind utilities;
    If your using SCSS copy & paste this into your styles.scss
>         @import "tailwindcss/base";
>         @import "tailwindcss/components";
>         @import "tailwindcss/utilities";
    6. That's all! Don't put TAILWIND_MODE into your angular environment. 
