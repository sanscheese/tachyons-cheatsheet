# Tachyons Cheatsheet

I had a lot of trouble while learning how to use Tachyons, there are a _ton_ of
new classes to learn and I have bad memory.

So, I decided to create this interactive cheatsheet. This project does not intend
to be source of the Tachyons truth or to replace the excellent documentation. Instead,
use it as your friendly companion.

## Development

### Dependencies

- Node.js v7.x

### Getting started

If you satisfy all the dependencies, go to the root of the project and install
the required node modules:

```bash
$ npm install
```

Then, just start your server by running:

```bash
$ npm run start
```

### Generating documentation

All the documentation is stored in `yml` files under the `docs` folder, this
files are parsed and converted to a single `json` file located in `app/assets/data.json`.

In order to parse the `yml` to `json` you need to run the `docs2json` script located
at the rot:

```bash
$ ./docs2json.sh
```

## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

All the code contained in this repository, unless explicitly stated, is
licensed under an MIT license.

A copy of the license can be found in the [LICENSE](LICENSE) file.
