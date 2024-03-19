# Hello

This branch dedicated to the first steps with Tailwind:

1. Installation
2. Exploration of the styles

---

# Demo prompt

## References

This prompt inspred by the video tutorial [Learn Tailwind CSS – Course for Beginners](https://youtu.be/ft30zcMlFao?si=hH2dncmJefrgOVqU) published on [freecodecamp.org](https://freecodecamp.org).

## Step 1: Install and do the config file for Tailwind

Go through the installation with `npm` guide: [https://tailwindcss.com/docs/installation](https://tailwindcss.com/docs/installation)

The `tailwind.config.js` will be customized, so it also tracks the content in `index.html`.

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}", "index.html"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

Check that the Tailwind is loaded in the sourse panel of Webdev tools.

![Tailwind installed screenshot](/img/tailwind-source.png)

## Step 2. Explore what Taiwind has to offer
