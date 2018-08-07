# NgMatSearchBar

The component creates a search-icon which expands a search-field on click. 

## Installation

Install the dependency via npm:

```bash
npm install ng-mat-search-bar --save
```

or yarn

```bash
yarn add ng-mat-search-bar
```

and import the module into your apps _app.module.ts_ like this:

```typescript
import { NgMatSearchBarModule } from 'ng-mat-search-bar';

...

@NgModule({
  ...,
  imports: [
    ...,
    NgMatSearchBarModule
  ],
  ...
})
```

and you also need to add Material Icons webfont by adding

```html
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```

to your _index.html_.

## Usage

You can use the component with its selector:

```angular
<mat-search-bar></mat-search-bar>
```

and then subscribe to the different events it is outputting:

- **onBlur**: fired when the search-field looses focus
- **onClose**: fired when the user closes the searchfield by clicking the close-button
- **onEnter**: fired when user presses enter-button in search-field
- **onFocus**: fired when user focuses the search-field
- **onOpen**: fired when the searchbar is shown

it also offers two public methods to open / close the searchbar:

- **open()**: opens the searchbar
- **close()**: closes the searchbar

## Contributions

Please don't hesitate to file an issue or send in a PR if you have any improvements or found bugs.