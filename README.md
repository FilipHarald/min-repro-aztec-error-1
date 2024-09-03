# min-repro-aztec-error-1

Running this example will result in the following error:

```
✘ [ERROR] Could not read from file: /home/filip/c/min-repor-aztec-error-1/my-vite-app/node_modules/node-stdlib-browser/esm/mock/empty.js/promises

    node_modules/@aztec/circuits.js/dest/structs/client_ivc_proof.js:2:20:
      2 │ import * as fs from 'fs/promises';
        ╵                     ~~~~~~~~~
```

This is a copy of https://github.com/critesjosh/aztec-wallet-ui-starter and with workaround removed.

## terminal 1

```bash
aztec start --sandbox
```


## terminal 2

```bash
cd my-vite-app
yarn
yarn dev
```
