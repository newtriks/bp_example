![Screenshot 2019-04-26 at 14 07 43](https://user-images.githubusercontent.com/31971/56810175-88d52d80-682d-11e9-8aec-93598c0f6971.png)

1. `cd node_modules/@blueprintjs/datetime/lib/css/`
1. Check path in `blueprint-datetime.css.map` for `_variables.scss`
1. Using path list dir for `_variables.scss` e.g. `ls ../../../../node_modules/@blueprintjs/core/src/common/`

## Error:

Output: `ls: ../../../../node_modules/@blueprintjs/core/src/common/: No such file or directory`

## Solution:

Step up another directory e.g. `ls ../../../../../node_modules/@blueprintjs/core/src/common/`

Output:

```
_color-aliases.scss             alignment.ts                    intent.ts
_colors.scss                    boundary.ts                     interactionMode.ts
_flex.scss                      classes.ts                      keys.ts
_mixins.scss                    colors.ts                       position.ts
_react-transition.scss          constructor.ts                  props.ts
_variables.scss                 elevation.ts                    utils
abstractComponent.ts            errors.ts                       utils.ts
abstractPureComponent.ts        index.ts
```
