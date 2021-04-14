# shadow-wiz npm package

## What is it?

Easily get perfect shadows around any image

## Installation

`npm i shadow-wizard --save`

## Using the wizard

```
import { shadowWiz } from "shadowWiz";

shadowWiz({
    shadow_type: "soft",
    padding: false
})
```

## Options

ShadowWiz supports 2 options, and are both optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)