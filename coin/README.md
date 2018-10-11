Please add this to /nomp/node_modules/stratum-pool/lib/algoProperties.js after running `npm install`

```
cryptonight: {
        hash: function(){
            return function(){
                return multiHashing.cryptonight.apply(this, arguments);
            }
        }
    }
```
