```python
from flask import Flask, request, jsonify
import requests

app=Flask(__name__)

@app.route('/activate_',
methods=['Post'])
url="https://your-api-endpoint.com/
active"
headers={
'x-api-key':'ADYEN_API_KEY',
'idempotency-key':
'YOUR_IDEMPOTENCY_KEY',
'content-type':'application/json'
}
data={
"merchantAccount":
"YOUR_MERCHANT_ACCOUNT",
"reference":"YOUR_REFERENCE",
"amount":{
"value":10000,
"currency":"USD"
},
"ACTIVATE":{
"type":scheme",
"encrypted card number":5156768927405004",
"encryptedExpiryMonth":"11"",
"encrypted ExpiryYear":"2029",
"encrypted ExpiryCode":"090"
}
}
