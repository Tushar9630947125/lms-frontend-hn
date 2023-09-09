# Lms Frontend

### Setup Instruction

1. Clone the project

```
     git clone https://github.com/Tushar9630947125/lms-frontend-hn.git
```

2. Move into the directory

```
     cd lms-frontend-hn
```

3. Install dependencies

```
     npm i
```

4. Run the server

```
      npm run dev
```
### Setup instruction  for tailwind

     [tail wind  official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindcss
```
     npm install -D tailwindcss

```
2. create tailwind config file
```
     npx tailwindcss init
```
3. add file extension to tailwaind  config file in the contents property
```
     "./src/**/*.{html,js,jsx,ts,tsx}"
```
4. Add the  tailwind directives at the top of the `index.css` file
```
     @tailwind base;
     @tailwind components;
     @tailwind utilities;
```
