# Svelte: First Look
This is the repository for the LinkedIn Learning course Svelte: First Look. The full course is available from [LinkedIn Learning][lil-course-url].

JavaScript frameworks and libraries keep growing, sprouting increasingly more dependencies along the way. Svelte—a new, lightweight component framework—marches into this tangle with a brush cutter, trimming down the weeds to provide a core set of key functionalities with zero dependencies. In this course, join Ray Villalobos as he helps you get up to speed with Svelte, explaining how to use it to create apps that please your users without making them wait. Learn how Svelte differs from frameworks like Angular and React, as well as how to use styles and preprocessors with Svelte, work with data across multiple components, use lifecycle methods to load data, and more.

*Psst — looking for a shareable component template? Go here --> [sveltejs/component-template](https://github.com/sveltejs/component-template)*

---

# svelte app

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.


## Deploying to the web

### With [now](https://zeit.co/now)

Install `now` if you haven't already:

```bash
npm install -g now
```

Then, from within your project folder:

```bash
cd public
now
```

As an alternative, use the [Now desktop client](https://zeit.co/download) and simply drag the unzipped project folder to the taskbar icon.

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public
```


### Instructor

**Ray Villalobos**

_Senior Staff Instructor at LinkedIn Learning_

[View on LinkedIn](https://www.linkedin.com/in/planetoftheweb?trk=lil_instructor)

[Other Courses by the Ray](https://www.linkedin.com/learning/instructors/ray-villalobos)

[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/svelte-first-look/

