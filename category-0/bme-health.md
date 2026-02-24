# BME Health Checks

## BME Status
Command:
```bash
akash query bme status --node https://testnetrpc.akashnet.net:443
collateral_ratio: "0.993189271245401067"
halt_threshold: "0.900000000000000000"
mints_allowed: true
refunds_allowed: true
status: mint_status_healthy
warn_threshold: "0.950000000000000000"
```

## Oracle Prices
```
pagination:
  next_key: null
  total: "0"
prices:
- id:
    base_denom: usd
    denom: akt
    height: "669"
    source: 1
  state:
    price: "0.305893640000000000"
    timestamp: "2026-02-23T15:09:39.932602614Z"
- id:
    base_denom: usd
    denom: akt
```

## Vault State
```
vault_state:
  balances:
  - amount: "30805514"
    denom: uact
  - amount: "100000000"
    denom: uakt
  remint_credits:
  - amount: "100000000"
    denom: uakt
  total_burned:
  - amount: "0"
    denom: uact
  - amount: "0"
    denom: uakt
  total_minted:
  - amount: "30805514"
    denom: uact
  - amount: "0"
    denom: uakt
```

## Wallet Balance
```
balances:
- amount: "499997411"
  denom: uakt
pagination: {}
```

## Provider Availability
```
leases: []
pagination:
  next_key: null
  total: "0"
```
