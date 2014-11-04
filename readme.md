# Foundation for Apps Template

This is the default template project for Foundation for Apps. It's powered by Node, Gulp, Angular, and libsass.

## Requirements

You'll need this software installed on your machine first:
 - [Node.js](http://nodejs.org/): use the installer provided on the Node.js website.
 - [Git](http://git-scm.com/downloads): use the installer provided on Git's website.

## Get Started

Clone this repository, where `app` is the name of your app.

```bash
git clone https://github.com/zurb/foundation-apps.git app
```

Change into the directory.

```bash
cd app
```

Install the dependencies. Running `npm install` will also automatically run `bower install` after. If you're running Mac OS or Linux, you may need to run `sudo npm install` instead, depending on how your machine is configured.

```bash
npm install
```

While you're working on your project, run:

```bash
npm test
```

This will compile the Sass and assemble your Angular app. **Now go to `localhost:8080` in your browser to see it in action.**

To run the compiling process once, without watching any files:

```bash
npm test build
```