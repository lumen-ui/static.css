# static.css

A drop-in collection of CSS styles to establish common stylings.

---

## Development

1. Ensure your environment has [Git](https://git-scm.com/), [Node.js](https://nodejs.org/en/), and [npm](https://www.npmjs.com/) installed.
2. Clone repository, run `git clone git@github.com:lumen-ui/static.css.git`.
3. Install dependencies, run `yarn`.
4. Make changes to the styles in the src directory, and perform one of the options:

   - Manually compile Sass to plain CSS, run `yarn sass`.
   - Watch for Sass changes to automatically compile to plain CSS, run `yarn sass-watch`.

5. To add [vendor prefixes](https://developer.mozilla.org/en-US/docs/Glossary/Vendor_Prefix) to the compiled `dist/static.css file`, run `yarn build`.

---

## Usage

We are currently in the process of publishing the static.css file for easy integration (e.g. `<link rel="stylesheet" href="https://unpkg.com/@lumen-ui/static.css" />`), until that is setup, you can do the following:

1. Download/clone the repository.
2. Copy/paste the `dist/static.css file` file into your project (e.g. inside your `styles/vendor` folder).
3. Link the stylesheet inside the head section of your HTML page, `<link rel="stylesheet" href="styles/vendor/static.css">`.
