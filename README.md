<h2>Introduction</h2>
using jest with typescript and es-module is not simple. But jest is popular and typescript and es-module are popular. jest does not work out of the box with typescript and es-modules. note the vitest does work out of the box with es module and typescript

<h2>Motivation</h2>
<p>How to use jest with typescript ? jest documentation suggest two solutions : <a href='https://jestjs.io/docs/28.x/getting-started#via-babel'>babel</a> and <a href='https://jestjs.io/docs/28.x/getting-started#via-ts-jest'>ts-node</a>. In this repository i will look into ts-jest</p>
<p>using with typescript should solve the jest es module problem - lets see about that</p>


<h2>setup</h2>

install dependencies
```
pnpm i -D jest typescript ts-jest @types/jest
```

create config file
```
npx ts-jest config:init
```

add to package.json
```
    "test": "jest"
```

<h2>usage</h2>

```
npm test
```

<h2>conclusion</h2>
using ts-jest work nicely with typescript and es module. the setup is very easy