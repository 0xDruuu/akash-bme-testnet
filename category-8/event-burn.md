# Event Emission - BurnACT

Command:
```bash
akash query tx BF22FB7B3EE39972A19BF2C36FA58A7F54F885F4641420A1A17EEF823B7B8856 --node https://testnetrpc.akashnet.net:443 --output json | jq '.events[] | select(.type == "message")'
[]
```
