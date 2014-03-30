Basket performace test
========================

Test performace on localhost and Google Chrome loading jQuery from Google CDN or from localStorage with Basket.js

Not cached (first load)

|              | Google CDN | Basket.js |
| ------------ | ------------- | ------------ |
| test 1 | 5 req, 34.1kb, 288ms  | 7 req, 94.4kb, 317ms |
| test 2 | 5 req, 34.1Kb, 334ms | 7 req, 94.4kb, 294ms |


Cached

|              | Google CDN (5 req, 233b) | Basket.js (5 req, 233b) |
| ------------ | ------------- | ------------ |
| test 1 | 242ms | 240ms |
| test 2 | 280ms | 276ms |
| test 3 | 256ms | 274ms |
| test 4 | 272ms | 287ms |
| test 5 | 271ms | 272ms |


