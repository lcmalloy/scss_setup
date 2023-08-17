# scss_setup
Common setup for scss styling on most projects


## Notes

### Install Vite
```
  npm create vite@latest
  Project name: //Choose project name
  Select Framework: //select choice of framework
```


### Purgecss

#### Install

```
purgecss: npm i vite-plugin-html-purgecss -D
```

#### vite.config.js
```
  import htmlPurge from "vite-plugin-html-purgecss"
  export default {
    plugins: [htmlPurge()],
  };
```
