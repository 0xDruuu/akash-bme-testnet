# Event Emission - Deployment Close

Command:
```bash
akash query tx 98B6A66D767B3C7D8A06B49BAB95CE1A668CCAC9927934B693A96516D27839E0 --node https://testnetrpc.akashnet.net:443 --output json | jq '.events[]'
{
  "type": "coin_spent",
  "attributes": [
    {
      "key": "spender",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "amount",
      "value": "5000uakt",
      "index": true
    }
  ]
}
{
  "type": "coin_received",
  "attributes": [
    {
      "key": "receiver",
      "value": "akash17xpfvakm2amg962yls6f84z3kell8c5lazw8j8",
      "index": true
    },
    {
      "key": "amount",
      "value": "5000uakt",
      "index": true
    }
  ]
}
{
  "type": "transfer",
  "attributes": [
    {
      "key": "recipient",
      "value": "akash17xpfvakm2amg962yls6f84z3kell8c5lazw8j8",
      "index": true
    },
    {
      "key": "sender",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "amount",
      "value": "5000uakt",
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
    }
  ]
}
{
  "type": "tx",
  "attributes": [
    {
      "key": "fee",
      "value": "5000uakt",
      "index": true
    },
    {
      "key": "fee_payer",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    }
  ]
}
{
  "type": "tx",
  "attributes": [
    {
      "key": "acc_seq",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj/7",
      "index": true
    }
  ]
}
{
  "type": "tx",
  "attributes": [
    {
      "key": "signature",
      "value": "nK/AaJYg4STVaUBP5Q30hhRW83BIXf/uixajTOomqU0QxCOLdFYvJNmgyLeFnuNOA/cyDn3cgCFT2RC8SkxZsg==",
      "index": true
    }
  ]
}
{
  "type": "message",
  "attributes": [
    {
      "key": "action",
      "value": "/akash.deployment.v1beta4.MsgCloseDeployment",
      "index": true
    },
    {
      "key": "sender",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "module",
      "value": "deployment",
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
  "type": "coin_spent",
  "attributes": [
    {
      "key": "spender",
      "value": "akash14pphss726thpwws3yc458hggufynm9x77l4l2u",
      "index": true
    },
    {
      "key": "amount",
      "value": "2000000uact",
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
  "type": "coin_received",
  "attributes": [
    {
      "key": "receiver",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "amount",
      "value": "2000000uact",
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
  "type": "transfer",
  "attributes": [
    {
      "key": "recipient",
      "value": "akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj",
      "index": true
    },
    {
      "key": "sender",
      "value": "akash14pphss726thpwws3yc458hggufynm9x77l4l2u",
      "index": true
    },
    {
      "key": "amount",
      "value": "2000000uact",
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
      "value": "akash14pphss726thpwws3yc458hggufynm9x77l4l2u",
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
  "type": "akash.deployment.v1.EventDeploymentClosed",
  "attributes": [
    {
      "key": "id",
      "value": "{\"owner\":\"akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj\",\"dseq\":\"979\"}",
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
  "type": "akash.deployment.v1.EventGroupClosed",
  "attributes": [
    {
      "key": "id",
      "value": "{\"owner\":\"akash1hc8ch6pygsyrscvhnx2tzmy3rqkrlwxn2cgahj\",\"dseq\":\"979\",\"gseq\":1}",
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
