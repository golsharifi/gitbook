# Contracts

The NDB token's smart contract address is:

```
0xf8028b65005B0B45f76988d2A77910186E7af4eF
```

The NDB token adopts Gnosis Safe to improve the decentralization of the project and Time-lock with reasonable latency for awareness on privileged operations.

The deployment of Gnosis Safe is at:&#x20;

```
0xdcB07f74F51ED68463d69dE23AeCe4173A527a35
```

With following owners/co-signers:&#x20;

```
0x5C8C2F55d54dAB9adBE4FA88387504bA9D411430 
0x834832feB6624bf2957540ca8078abab9b2a6d80 
0xC9904d6cFFF6eA40b6767e6516A83B45C140486b
```

The Watt deploy the ownable contracts behind OpenZepplin's timelock contract with a delay of 48 hours.

The Watt also use the gnosis safe wallet to send transactions to the timelock contract. The team has set the NDBstaking, NDBreferral, NDBstaking\_referral contract owner to be a timelock contract with a delay of 48 hours.

The deployment of timelock contract is at:&#x20;

```
0x74Fb4583aeA7a5612914dcefeeAFA5C9E21cE9B4
```

The timelock admin is a Gnosis multisig wallet that you can find below: \
[https://gnosis-safe.io/app/bnb:0xdcB07f74F51ED68463d69dE23AeCe4173A527a35](https://gnosis-safe.io/app/bnb:0xdcB07f74F51ED68463d69dE23AeCe4173A527a35)
