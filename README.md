[![CI](https://github.com/eisberg-labs/angular-components/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/eisberg-labs/angular-components/actions/workflows/ci.yml)
# Angular Components

Welcome to Eisberg Labs Angular Components,
repository contains custom Angular components that we use in our projects.

[Barcode Scanner](./projects/ngx-barcode-scanner)  
[Ngx Size Me](./projects/ngx-size-me)  
[Ngx Strength Meter](./projects/ngx-strength-meter)  

## Demo and Documentation
[Visit for examples and documentation](https://www.amarjanica.com/projects/angular-components).


## Publishing

```
npm test
npm run build-all
lerna version --no-private
lerna publish from-git --no-private
lerna publish from-package --registry https://npm.pkg.github.com
```
## License
MIT © [Eisberg Labs](http://www.eisberg-labs.com)
