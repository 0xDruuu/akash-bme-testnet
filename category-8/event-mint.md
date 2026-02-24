# Event Emission - MintACT

Command:
```bash
akash query tx 2F39056E2694592F90143FF5FA0A1102CFF470CCE8E9B2988431A8971C94D27A --node https://testnetrpc.akashnet.net:443 --output json | jq '.events[] | select(.type == "message")'
{
  "type": "message",
  "attributes": [
    {
      "key": "sender",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    }
  ]
}
{
  "type": "message",
  "attributes": [
    {
      "key": "action",
      "value": "/akash.bme.v1.MsgMintACT",
      "index": true
    },
    {
      "key": "sender",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "module",
      "value": "bme",
      "index": true
    },
    {
      "key": "msg_index",
      "value": "0",
      "index": true
    }
  ]
}
{
  "type": "message",
  "attributes": [
    {
      "key": "sender",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "msg_index",
      "value": "0",
      "index": true
    }
  ]
}
```
