# docs

### Frontend Basics
- Avoid coding <p> tags
  
### Naming Things
- Have design / wires define section names
- `<div class="semantic-name helper-class-1 helper-class-2 js-element">`

### Bullet Proofing / scalibility
- Ensure lack of content wont leave empty spaces
### File organizing

DRY / KIS

https://www.interaction-design.org/literature/article/kiss-keep-it-simple-stupid-a-design-principle
https://en.wikipedia.org/wiki/Don%27t_repeat_yourself

## Styling approach
- Flexible w approach
- Helper classes
- Sematntic 


- CSS margin bottom
- CSS media queries within rules

## Font Families
```css
// Not ideal, creating a new "family" for bold
@font-face {
  font-family: 'Object-Sans-Regular';
  src: url('/fonts/ObjectSans-Regular.woff');
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: 'Object-Sans-Bold';
  src: url('/fonts/ObjectSans-Bold.woff');
  font-weight: 400;
  font-style: normal;
}

```

```css
// Better! Regular are bold are in the same family.
@font-face {
  font-family: 'Object-Sans-Regular';
  src: url('/fonts/ObjectSans-Regular.woff');
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: 'Object-Sans-Regular';
  src: url('/fonts/ObjectSans-Bold.woff');
  font-weight: 400;
  font-style: normal;
}
```

[link to Wiki!](https://github.com/d-e-v-group/docs/wiki)
