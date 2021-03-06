# Running

There are two options to run and showcase your presentation:

You could either publish and showcase your deck online, which can then be accessed by the audience via navigating to its appropriate URL.

Or you could showcase your deck locally, by running it in your favorite web browser using the integrated dev server provided by the [DeckDeckGo] starter kit with the default access URL [http://localhost:3000](http://localhost:3000).

## Local

To run your presentation, execute the following command in a terminal (it builds/bundles your slides and listens to modifications):

```bash
npm run start
```

If you wish to develop your presentation without adding it to the list of available deck of the remote control, run the following command instead:

```bash
npm run start-no-remote
```

> Furthermore, to serve your deck, both above commands are watching your presentation's source files for changes and will trigger a new build and reload in case of modifications

[lite-server](https://github.com/johnpapa/lite-server) is use as the integrated dev server.

## Online

If you are looking to showcase your presentation from an online URL, have a look to the next chapter [publishing](/docs/publishing) before deploying your deck on your hosting solution.

[DeckDeckGo]: https://deckdeckgo.com 