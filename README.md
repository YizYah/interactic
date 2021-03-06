
[//]: # ( ns__file unit: standard, comp: README.md )

[//]: # ( ns__custom_start beginning )

[//]: # ( ns__custom_end beginning )

[//]: # ( ns__start_section intro )

[//]: # ( ns__custom_start description )
interactic
======
executes a sequence of interactive processes

[//]: # ( ns__custom_end description )

[//]: # ( ns__custom_start afterDescription )

[//]: # ( ns__custom_end afterDescription )

[//]: # ( ns__custom_start badges )

[//]: # ( ns__start_section usageSection )

[![codecov](https://codecov.io/gh/YizYah/interactic/branch/main/graph/badge.svg?token=019QO4XK1Z)](https://codecov.io/gh/YizYah/interactic) 
[![Version](https://img.shields.io/npm/v/interactic.svg)](https://npmjs.org/package/interactic)
[![Downloads/week](https://img.shields.io/npm/dw/interactic.svg)](https://npmjs.org/package/interactic)
[![License](https://img.shields.io/npm/l/interactic.svg)](https://github.com/YizYah/interactic/blob/master/package.json)

[![Geenee](https://img.shields.io/badge/maintained%20by-geenee-brightgreen)](https://npmjs.org/package/geenee)
[![Template](https://img.shields.io/badge/template-ts--packrat-blue)](https://npmjs.org/package/ts-packrat)

[//]: # ( ns__custom_end badges )

[//]: # ( ns__end_section intro )


[//]: # ( ns__start_section api )


[//]: # ( ns__custom_start APIIntro )
Uses execa to call a sequence of commands.

Include with `npm i interactic magicalstrings@0.1.14`
Then you can call it like this:
```
const interactic = requre 'interactic'
import { CommandSpec } from 'magicalstrings';

const tempCommandSpecs: CommandSpec[] = [
  {
    title: 'create react app'
    file: 'create-react-app
  },
];

const codeDir = '/tmp/interactiveSequenceTest';

async () => {
  await interactic(tempCommandSpecs, codeDir)
})
```

# API
```
async function interactic(commandSpecs: CommandSpec[], 
codeDir: string)
```
Check out the CommandSpec type in magicalstrings for more info about that.  The `codeDir` string is directory where you want the command to be executed. 

[//]: # ( ns__custom_end APIIntro )


[//]: # ( ns__custom_start constantsIntro )
## General Constants and Commands

[//]: # ( ns__custom_end constantsIntro )



[//]: # ( ns__start_section types )


[//]: # ( ns__end_section types )


[//]: # ( ns__end_section api )

