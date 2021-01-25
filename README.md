# Coinbase Demo

Installation Instructions.

  - Install node_modules (coinbase)
  - Run command "node app.js"
  - Send application/json rwequest to endpoint http://127.0.0.1:3000/send
  
#Parameters (application/json)
- to: wallet to send money to
- amount: value to send
- currency: E.g. BTC, LTC, ETH
- accountID: Optional. Default is primary

# Sample request!
-URL: 127.0.0.1:3000/send

-Using address
```json
{
  "to": "3ER3MpfV5EyzdG9WosfQycfeb4rA2B2FTM",
  "amount": 0.01,
  "currency": "BTC",
  "accountID": ""
}
```

-Using email
```json
{
  "to": "example@emai.com",
  "amount": 0.01,
  "currency": "LTC",
  "accountID": ""
} 
```



