# LuchowSwap SDK

Forked from the [PancakeSwap SDK](https://github.com/pancakeswap/pancake-swap-sdk/commit/762acf823a5870033b3d58a2724e8078f272a1a0).

You can refer to the PancakeSwap SDK documentation [pancakeswap.finance](https://docs.pancakeswap.finance/get-started).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/LuchowSwap/luchow-swap-sdk.git
```

Move into the luchow-swap-sdk working directory

```sh
cd luchow-swap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
