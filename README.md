-H 'x-api-key: ADYEN_API_KEY' \
-H 'idempotency-key: YOUR_IDEMPOTENCY_KEY' \
-H 'content-type: application/json' \
-d '{
  "merchantAccount": "YOUR_MERCHANT_ACCOUNT",
  "reference": "My first Adyen",
  "amount": {10000
  "currency": "USD"
  },
	"ACTIVATE": {
    "type": "scheme",
    "encryptedCardNumber": "test_5156768927405004",
    "encryptedExpiryMonth": "11",
    "encryptedExpiryYear": "2029",
    "encryptedSecurityCode": "090"
  }
}'
