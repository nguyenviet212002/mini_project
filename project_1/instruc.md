\*pug
npm i -g pug-cli
pug --version
mkdir -p pug-examples
cd pug-examples
touch index.pug
pug -w . -o ./html -P

\*sass
sass --version
npm install -g sass
sass sass/app.scss css/app.css --watch
sass --watch style.scss:style.css
