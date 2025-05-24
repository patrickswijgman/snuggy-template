# Snuggy template

A game created with the [snuggy](https://github.com/patrickswijgman/snuggy) engine.

## Getting started

Install dependencies

```shell
npm install
```

Run the game

```shell
npm start
```

## Adding assets to the game

Place your textures, sounds, fonts and any other assets for your game in the `public` folder. Refer to them without the `public` prefix in your code.

```typescript
// load 'public/textures/player.png' in your setup function like so:
await loadTexture("textures/player.png");
```

## Build for a website

```shell
npm run build
```

And upload the files from the `dist` directory to your web server.
