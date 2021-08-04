# Utility for ordering pair of assets in (amount_asset, price_asset)

![Build Status](https://api.travis-ci.org/wavesplatform/assets-pairs-order.svg?branch=master)

## Example:

```
yarn add @decentralchain/assets-pairs-order
```

```javascript
import { createOrderPair, MAINNET_DATA } from '@decentralchain/assets-pairs-order'

const orderPair = createOrderPair(MAINNET_DATA);
orderPair(
  'DNhP2zAH5HM1kdUSmxcBqs8RP4vvUgRFc1YgAKkfPmPD',
  'FxSm86qcEw8wGfpX3T7X5fsnuK5XxYA6ZfVYJja29vMA'
)

/* [
    'FxSm86qcEw8wGfpX3T7X5fsnuK5XxYA6ZfVYJja29vMA',
    'DNhP2zAH5HM1kdUSmxcBqs8RP4vvUgRFc1YgAKkfPmPD',
  ]
*/

## Browser

For using in browser include dist/browser.js
```
