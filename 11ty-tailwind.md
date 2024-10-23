npm init -y
npm install -D 11ty/eleventy
npx eleventy
npx eleventy --serve

npm install -D tailwindcss
npx tailwindcss init
npx tailwindcss -i ./tailwind.css -o ./_site/css/styles.css --watch
