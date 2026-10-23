# Resources of the Wild

A searchable compendium of the in-game items in _The Legend of Zelda: Breath of the Wild_. Pick a category (food, creatures, equipment, materials, monsters or treasure) and an entry, and it pulls the details, image, locations, drops and stats from the free [Hyrule Compendium API by Aarav Borthakur](https://github.com/gadhagod/Hyrule-Compendium-API). Built with React 18 and Vite, with a small custom hook that caches each category's entries, to get more comfortable developing in React.

A pre-AI project from 2023.

The API's original address (`botw-compendium.herokuapp.com`, which the app still calls) no longer responds, so the app runs but can't load entries; the screenshot below is from 2023.

![Resources of the Wild showing the Royal Shield entry from the Equipment category, with its image, description, locations and attack and defense stats](readme.png)

## Run it locally

1. `npm ci`
2. `npm run dev`, then open the local URL Vite prints
