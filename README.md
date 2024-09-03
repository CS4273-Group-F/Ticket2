# Ticket2

NOTE: I'm not sure why, but I can only run 1 app at a time, or the locator wouldn't load

# React

## Using create-react-app

1. ```npx create-react-app demo-app_cra```
2. ```cd demo-app_cra```
3. In src, delete
    - App.test.js
    - logo.svg
    - reportWebVitals.js
    - setupTests.js
4. In src, Edit
    - index.html
    - App.js
    - index.js
    - App.css
5. ```npm start```


## Using Vite
1. ```npm create vite@latest demo-app_vite```
2. name the project, select a framework and a variant
3. ```cd demo-app_vite```
4. ```npm install```
5. In src, Edit
    - index.html
    - index.css
    - App.jsx
    - App.css
6. ```npm run dev```

# Svelte
1. ```npm create svelte@latest demo-svelte-app```
    - Select "Skeleton project"
    - Choose "No" for TypeScript
    - Don't select any additional options
2. ```cd demo-svelte-app```
3. ```npm install```
4. Delete
    - src/routes/about
    - src/routes/sverdle
    - src/routes/Counter.svelte
    - src/routes/Header.svelte
5. Edit
    - src/app.html
    - src/routes/+page.svelte
    - src/routes/+layout.svelte
    - src/app.css
6. ```npm run dev```

# .NET
1. install .NET SDK
2. ```dotnet new web -n demo-dotnet-app```
3. ```cd demo-dotnet-app```
4. edit /Program.cs
5. create /wwwroot and /wwwroot/index.html
6. edit /wwwroot/index.html
7. ```dotnet run```
