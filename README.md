# Repro steps

1. `git clone https://github.com/csalvato/cra-jest-enzyme.git`
2. `cd cra-jest-enzyme`
3. `npm test`
4. Notice errors

<img width="569" alt="image 2017-04-09 at 11 37 57 am" src="https://cloud.githubusercontent.com/assets/1158152/24838605/01290296-1d19-11e7-80be-55f52c0a8cdc.png">

```
Test suite failed to run

    TypeError: expect.addSnapshotSerializer is not a function

      at Object.<anonymous> (node_modules/jest-enzyme/lib/index.js:23:8)
      at Object.<anonymous> (src/setupTests.js:1:156)
```
