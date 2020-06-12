# Node Webpack

### Inicializar proyecto
```bash
npm init -y
```

### Instalar dependencias
```bash
npm i webpack webpack-cli
```

### Modificar package.json
```json
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "pack": "webpack"
  },
```

### Creación de código
Armaremos en este caso denominada **src** y en ella, **index.js**
```javascript
let palabras = ['lorem', 'ipsum', 'dolor'];

for (x of palabras) {
  console.log(x);
}
```

### Empaquetar código
```bash
npm pack
```