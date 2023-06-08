# React typing app

![image](https://github.com/AnarbekovAlt/react-typing/assets/62358513/c7eacafa-9beb-436e-9b2a-279fcb83e093)
![image](https://github.com/AnarbekovAlt/react-typing/assets/62358513/a854f57a-67bd-479b-a4ce-970480abb2ef)

A react application to practice your typing skills. The app was built using:

- Vite
- Typescript
- React
- Redux Toolkit
- React Bootstrap
- Bacon Ipsum API (for English text) and FishText API (for Russian text)

## App features

At the start of the app you can:

- choose a language of text you want to type.
- choose how large text will be

While typing:

- if you type the correct key, the character will be green, if you make a mistake, it will be highlighted in red.
- if you typed a key with the wrong keyboard layout (keyboard language), the corresponding message will be shown.
- displays the elapsed time, the number of errors, the total number of characters typed, typing speed, accuracy.
- you can click the "Reset" button to reset the text and text options

After completing typing:

- a modal window is displayed with your results and a reset button

## How to run

```bash
npm i
npm run dev
```
