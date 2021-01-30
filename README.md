# box-shadow-on-image

## What is this?

Get perfect shadows every time for the non-designer

## Installation

`npm i boxshadowonimage --save`

Then...

```
import {boxshadowonimage} from 'boxshadowonimage';

boxshadowonimage({
    shadow_type: 'soft',
    padding: false
});
```

### Options

boxshadowonimage supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)