# generator-yeoman-timwe-angular ![Build Status] (https://travis-ci.org/Fateicha/generator-yeoman-timwe-angular.svg?branch=master)

> [Yeoman](http://yeoman.io) generator


## Getting Started

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

*You will need Noje.js installed in your system. Go to: https://nodejs.org/*

```bash
npm install -g yo
```

### Yeoman Generators

Yeoman travels light. He didn't pack any generators when he moved in. You can think of a generator like a plug-in. You get to choose what type of application you wish to create, such as a Backbone application or even a Chrome extension.

Since this is a private repo we need to install the generator with the following flow:

To install generator-yeoman-timwe-angular, run:

*Ask for permisssion if you don't have it yet.*

```bash
git clone https://github.com/Fatxx/generator-yeoman-angular
```

Then navigate inside that folder:

```bash
cd generator-yeoman-angular
```

And run:

```bash
npm link
```

Finally, go to a desired directory and initiate the generator:
```bash
cd /path/to/your/app/directory
yo yeoman-angular
```

## License

MIT
