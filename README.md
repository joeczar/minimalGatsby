# Minimal Gatsby

```
$ mkdir minGatsby && cd minGatsby
$ npm init -y/
$ yarn add react react-dom gatsby
$ mkdir -p src/pages && cd src/pages
$ touch index.js
$ cat >> index.js << EOF
    import React from 'react'
    const Home = () => <h1>Hello Gatsby!</h1>
    export default Home;
    EOF
$ cd ../..
$ gatsby develop
```

That's it.

Or, you could just use gatsby to build this repository...

````gatsby new minGatsby https://github.com/joeczar/minimalGatsby.git
cd minGatsby && gatsby develop````
