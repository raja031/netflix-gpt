# create a new app
npx create-react-app netflix-gpt

# install tailwind css and update the config chanegs
npm install -D tailwindcss@3
npx tailwindcss init

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
# In css file,add the below code
@tailwind base;
@tailwind components;
@tailwind utilities;