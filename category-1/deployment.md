# Deployment Creation

## Deployment DSEQ 979
Txhash: `B3B5C9BA191F41AC0B7DFDFED062D48C7CD021A7E838D766B38AB6EE0AD9AD8A`
Deposit: 2,000,000 uact

Status:
```json
deployment:
  created_at: "980"
  hash: 5kNtmcQ9SzdEzlbxF3xAGdGXop2nVMCyA6j4Upewa/g=
  id:
    dseq: "979"
    owner: akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj
  state: active
escrow_account:
  id:
    scope: deployment
    xid: akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj/979
  state:
    deposits:
    - balance:
        amount: "2000000.000000000000000000"
        denom: uact
      direct: false
      height: "980"
      owner: akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj
      source: balance
    funds:
    - amount: "2000000.000000000000000000"
      denom: uact
    owner: akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj
    settled_at: "980"
    state: open
    transferred:
    - amount: "0.000000000000000000"
      denom: uact
groups:
- created_at: "980"
  group_spec:
    name: akash
    requirements:
      attributes:
      - key: host
        value: akash
      signed_by:
        all_of: []
        any_of: []
    resources:
    - count: 1
      price:
        amount: "1000.000000000000000000"
        denom: uact
      resource:
        cpu:
          attributes: []
          units:
            val: "500"
        endpoints:
        - kind: SHARED_HTTP
          sequence_number: 0
        gpu:
          attributes: []
          units:
            val: "0"
        id: 1
        memory:
          attributes: []
          quantity:
            val: "536870912"
        storage:
        - attributes: []
          name: default
          quantity:
            val: "1073741824"
  id:
    dseq: "979"
    gseq: 1
    owner: akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj
  state: open
```

## Insufficient Funds Test
```
Enter keyring passphrase (attempt 1/3):
Error: rpc error: code = Unknown desc = rpc error: code = Unknown desc = failed to execute message; message index: 0: deposit invalid: insufficient balance [cosmos/cosmos-sdk@v0.53.5/baseapp/baseapp.go:1052] with gas used: '56063': unknown request
```

## Minimum Deposit Test
```
Enter keyring passphrase (attempt 1/3):
Error: rpc error: code = Unknown desc = rpc error: code = Unknown desc = failed to execute message; message index: 0: Deposit too low - 1 < 500000uact: Deposit invalid [pkg.akt.dev/go@v0.2.0-b12/node/deployment/v1beta4/params.go:58] with gas used: '53337': unknown request
```

## Multiple Deployments
- Deployment A (DSEQ 1630): txhash `F8B97E82735F7E61DD366CC2DB6AA8521E39522FBAAA26CC1087B2482279BC1C`
- Deployment B (DSEQ 1633): txhash `D85B5A42AE4C1AF19AAAFB7E53FF52DB97D2948801BA0BB30E232A4E2E18CCD2`
