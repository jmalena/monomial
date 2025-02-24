[monomial](../wiki/globals) / unrank

# Function: unrank()

> **unrank**(`order`, `rank`, `c`): `number`[]

Defined in: [index.ts:60](https://github.com/jmalena/monomial/blob/edfd1be5dabff441cdca5c794832580f122d1d43/src/index.ts#L60)

Returns the `k`-tuple `u` corresponding to a given `rank` (1-based) within the given monomial order under constraints `c`.

## Parameters

### order

`Order`

The monomial order.

### rank

`bigint`

The 1-based rank of the `k`-tuple `u`.

### c

`OrderConstraints`

The constraints applied on the monomial order.

## Returns

`number`[]

The `k`-tuple corresponding to the `rank` in the given monomial order.
