
***
# checking the version of node js

`node --version`


# checking the version of npm

`npm --version`

# updating the npm version

`npm install -g npm@latest --force.`


# setting up new npm package

`npm init`


# installing nodemon globally
`npm install -g nodemon`

`npm i --save--dev nodemon`

# installing express js package
`npm install express --save`

# installing packages
`npm i`
or
`npm install`


***
# Exporting and importing file

  ## for exporting
      constant={
                  name='tulsi'
                  roll='181346'
                }
     `module.export = constant`

  ## for importing
     `const constant = require('./filename)`
***
# module wrapper function
`(function(exports,require,module,_filename,_dirname){`

`)};`

# Fs module
```
const fs = require('fs');
fs.readFile('file.txt','utf8',(err,data)=>{
    console.log(err,data)
});
console.log('finished reading file');


```
<p>
finished reading file is displayed before file constent
</p>

## synchronize this file’s in-core state with the storage device.
```const fs = require('fs');

const a = fs.readFileSync('file.txt')
console.log(a.toString());
console.log('finished reading file');
```

<p>
finished reading file is displayed after file content
</p>






