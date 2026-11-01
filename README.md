# javascript_projects

JavaScript practice projects, from language fundamentals to small apps built with the DOM, async code and modules. Code follows a structured JavaScript course and is organised by topic.

## Contents (in `JavaScript/`)
| Folder | Topic |
|---|---|
| `00` to `03` | Basics (ES5), fundamentals, editor setup and debugging |
| `05-DOM-and-Events_Guess-My-Number`, `06-…_Modal`, `07-…_Pig-Game` | DOM manipulation and events, small browser games |
| `08` to `10` | How JavaScript works, data structures and operators, functions in depth |
| `11-Working-with-Arrays` | Array methods, Bankist banking app |
| `13-Advanced-DOM-Bankist` | Advanced DOM: scrolling, tabs, lazy loading, sliders |
| `14-OOP` | Classes, prototypes, inheritance |
| `15-Mapty App` | Geolocation and a workout tracker map app |
| `16-Asynchronous` | Promises, async/await, fetch and REST APIs |
| `17-Modern-JS-Modules-Tooling` | ES modules, CommonJS, npm and Parcel |
| `18-Forkify_App` | Recipe search app: MVC architecture, SCSS, Parcel build |

## Running the apps
Most folders are plain HTML and JavaScript: open `index.html` in a browser. The Forkify app needs Node.js:
```bash
cd JavaScript/18-Forkify_App
npm install
npm start
```

## Notes
- Course exercises, kept as a record of practice.
- The Forkify API key is not included (masked as `xxxx`). The original free API this app used is no longer available, so the app won't load recipes as it stands.
- Generated build output (`dist/`), `node_modules` and `.parcel-cache` are not committed.
