# TACKYONS

Functional css for one specific human.

A trimmed down and hacked up version of the wonderful [Tachyons](https://github.com/tachyons-css/tachyons/) that suits my needs and preferences.

### Local Setup

Clone the repo from github and install dependencies through npm.

```
git clone https://github.com/lol-russo/tackyons.git
cd tackyons
npm install
```

#### Dev

Compile all of your changes by running

```npm start```

This will output both minified and unminified versions of the css to the css directory and watch the src directory for changes.
It's aliased to the command:

```npm run build:watch```

If you'd like to just build the css once without watching the src directory run

```npm run build```

If you want to check that a class hasn't been redefined or 'mutated' there is a linter to check that all of the classes have only been defined once. This can be useful if you are using another library or have written some of your own css and want to make sure there are no naming collisions. To do this run the command

```npm run mutations```

## License

MIT
