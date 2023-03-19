Test Event Name
negativeAgeError

Response
{
  "sessionAttributes": {},
  "dialogAction": {
    "type": "ElicitSlot",
    "intentName": "recommendPortfolio",
    "slots": {
      "firstName": "John",
      "age": null,
      "riskLevel": "Low",
      "investmentAmount": "5000"
    },
    "slotToElicit": "age",
    "message": {
      "contentType": "PlainText",
      "content": "You should be between 0 and 65 years old"
    }
  }
}

Function Logs
/var/runtime/botocore/vendored/requests/__init__.py:179: DeprecationWarning: You are using the module 'botocore.vendored.requests'.  This dependency was removed from Botocore and will be removed from Lambda. https://aws.amazon.com/blogs/developer/removing-the-vendored-version-of-requests-from-botocore/. Install the requests package, 'import requests' directly, and use it instead.
warnings.warn(_WARNING_MSG, DeprecationWarning)
START RequestId: 1f850245-c7f0-45cb-beb7-2d256dea4e6b Version: $LATEST
END RequestId: 1f850245-c7f0-45cb-beb7-2d256dea4e6b
REPORT RequestId: 1f850245-c7f0-45cb-beb7-2d256dea4e6b	Duration: 15.39 ms	Billed Duration: 16 ms	Memory Size: 128 MB	Max Memory Used: 45 MB	Init Duration: 243.70 ms

Request ID
1f850245-c7f0-45cb-beb7-2d256dea4e6b