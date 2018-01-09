# Evaluation of OASGraph with APIs.guru APIs

## Prerequisite: Load data
Run:
```
node apis_guru_test.js
```
...to load APIs.guru APIs into `tmp` subfolder in the main directory of OASGraph.

## Run evaluation
Run:
```
node eval_apis.guru.js <limit>
```

`limit` determines the maximum number of Swagger files to evaluate.