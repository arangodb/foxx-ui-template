# foxx-api-keys
A minimalistic ui template for ArangoDB for foxx using pure css

Please use components provided by Pure (Grids, Forms, Buttons, Tables, Menus):  
* Documentation: http://purecss.io/

Font-Awesome included:
* Documentation: http://fortawesome.github.io/

# Usage
You need grunt to see your possible modifications. Install grunt and grunt-cli using npm. Then install all dependencies. Afterwards you can start generating the files.

```sh
npm install -g grunt 
npm install -g grunt-cli
npp install 
grunt (or grunt watch)
```

# Folder Structure
```sh
└── frontend
    ├── css                     <- static css files (include them in scss/style.scss)
    ├── fonts                   <- additional fonts
    ├── html                    <- html files
    ├── js                      <- js files
    └── scss                    <- sass files for css generation
└── build                       <- location of generated files
```
