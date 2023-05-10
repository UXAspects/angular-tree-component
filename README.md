# angular tree component

This is a fork of `@circlon/angular-tree-component` adding support for Angular 16+. There is no support for Angular 15 or below, and there are no plans to add any new features or fixes, this is simply a fork to allow Angular 16+ to use the library.

## Getting started

Install `angular-tree-component`:

`npm install @ux-aspects/angular-tree-component`

Import `TreeModule`:

```
import { TreeModule } from '@ux-aspects/angular-tree-component';

@NgModule({
  declarations: [AppComponent],
  imports: [TreeModule],
  bootstrap: [AppComponent]
})
export class AppModule {}
```

Add css to `styles.scss` or include in `angular.json`:

```
@import '~@ux-aspects/angular-tree-component/css/angular-tree-component.css';
```

## Docs, Demos & More

The API Reference is still in our old documentation for now:

[https://circlongroup.github.io/angular-tree-component/](https://circlongroup.github.io/angular-tree-component/)

## Angular supported version

angular-tree-component supports angular 16+
