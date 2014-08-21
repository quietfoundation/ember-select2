[Ember Select2](https://github.com/quietfoundation/ember-select2)
==========

This is a fork of [ember-select2](https://github.com/Frozenfire92/ember-select2) for the purpose of enhancing customization of the formatting used in the component.

#### Authors:
- [Stefan Fochler](https://github.com/iStefo)
- [Joel Kuntz](https://github.com/Frozenfire92)
- [Brad Osgood](https://github.com/bosgood)

## Usage

1) Install via Bower

```bash
bower install --save git@github.com:quietfoundation/ember-select2.git
```

2) Import the library in your `Brocfile.js`:

```js
app.import('vendor/ember-select2/build/lib.js');
```
**note your version of jquery may differ**

3) Use in your project

```handlebars
{{select-2 content=pizzas value=testResult placeholder="Select one"}}
```

See [index_controller.js](https://github.com/Frozenfire92/ember-select2/blob/master/app/scripts/controllers/index_controller.js) and [index.hbs](https://github.com/Frozenfire92/ember-select2/blob/master/app/templates/index.hbs) for examples in this repository.

See [Here](https://istefo.github.io/ember-select-2/#/examples) for more detailed examples.


## Developing

After cloning the repository, install the library dependencies.

```bash
npm install
bower install
```

Then build with `grunt`.

```bash
grunt serve
```
