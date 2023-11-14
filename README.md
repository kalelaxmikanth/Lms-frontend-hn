# LMS frontend
### setup instruction
clone the project
https://github.com/kalelaxmikanth/Lms-frontend-hn.git
move into the directory
cd lms-frontend
install dependencies 
npm install
run the server
npm run dev

npm install -D tailwindcss 
npx tailwindcss init
content: ["./src/**/*.{html,js,jsx,ts,tsx}"] in config.js file
add this in index.css
 @tailwind base;
@tailwind components;
@tailwind utilities;