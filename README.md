# editore.js link plugin [![npm version](https://badge.fury.io/js/editore-link-plugin.svg)](http://badge.fury.io/js/editore-link-plugin)

#### install
Available on npm: `npm install editore-link-plugin` or [directly download](https://github.com/evandroeisinger/editore-link-plugin.js/raw/master/src/editore-link-plugin.js)

#### basic usage
It's easy to use! Load [editore.js](https://github.com/evandroeisinger/editore.js) into your application, instantiate it and register the new **edition** plugin.

```javascript
var editore = new Editore(document.getElementById('editor')),
    LinkPlugin;

// Global
LinkPlugin = window.EditoreLinkPlugin;
// CommonJS
LinkPlugin = require('editore-link-plugin');

// then register!
editore.registerEditionPlugin(LinkPlugin);
```
---
#### support
- chrome: ?
- firefox: ?
- safari: ?
- internet explore: ?


---
#### contribute
Everyone can contribute! Finding bugs, creating issues, improving editor it self or creating components.
Every contribution will be welcomed! :santa: 

**Fork it** -> **Branch it** -> **Test it** -> **Push it** -> **Pull Request it** :gem:  
