## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```


1. Sign in [https://supabase.com/]Supabase Account.
2. Create database table with name "Mixes" (you can change it whenever you want)
3. Add the following columns:

NAME        |       TYPE        |       Defauñt value
id                  int8
created_at          timestamptz         now()
method              text                NULL
rating              int8                NULL

4. Click "Save"
5. Once downloaded, navigate to the project directory in a terminal and run npm install to install all the project dependencies.
6. In the project directory, run npm start to run the app & view it in a browser at http://localhost:3000.
