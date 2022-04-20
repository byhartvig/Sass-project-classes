# Sass-type-scale
### Kickstart your next project with predefined classes that help increase your productivity and make it easily accessible to change and developers we.

The project is in progress and below you can follow its progress, what has been done and what is in the pipeline.
- [x] Typo
- [x] Colors
- [ ] Checkboxes
- [ ] Radiobuttons
- [ ] Various inputfields (String, Int, Textarea etc...)
- [ ] Buttons

SCSS functions for the typography are borrowed from ModernCss.Dev[^1].

### Typo
For now, help classes are generated for headers and body texts. The project is under development and help classes for lists will be added in the near future.

**Headings**
``` Html
typo__headings--*
```
**The "*" can be replaces with numbers from 1 to 4.**

### Example
``` Html
<h1 className='typo__headings--1'></h1>
```

The classes for the body texts are the following
1. **typo__body--default**
2. **typo__body--bold**
3. **typo__body--caption**
4. **typo__body--small**

The typography uses the default type ratios: perfectFourth (1.333) but this can be changed to the following ratios:
1. minorSecond (1.067)
2. majorSecond (1.125)
3. minorThird (1.2)
4. majorThird (1.25)
5. perfectFourth (1.33)
6. augmentedFourth (1.414)
7. perfectFifth (1.5)
8. goldenRatio (1.618)

### Colors
The colours are defined in variables with HSL colour codes which are easy to change. 
There are 8 colour categories defined:
1. Primary
2. Secondary
3. Info
4. Success
5. Warning
6. Error
7. Accent
8. Greys

All colours have 7 different shades which are defined in HSL

### Color classes
Color classes are prefixed with "color__" followed by color category and shade.
Shades run from 100-700 where 100 is the lightest and 700 is the darkest

**Example**
``` HTML
<h1 className='color__info--600'></h1>
```
As with colors, background colors are also predefined with "background__"
**Example**
``` HTML
<div className='backgroundColor__greys--200'></div>
```
[^1]: [Link to the article](https://moderncss.dev/generating-font-size-css-rules-and-creating-a-fluid-type-scale/)



