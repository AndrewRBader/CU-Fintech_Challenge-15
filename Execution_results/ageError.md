Test Event Name
ageError

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
START RequestId: 47124779-d771-4cdd-b6b7-c54ea9f29e80 Version: $LATEST
END RequestId: 47124779-d771-4cdd-b6b7-c54ea9f29e80
REPORT RequestId: 47124779-d771-4cdd-b6b7-c54ea9f29e80	Duration: 1.86 ms	Billed Duration: 2 ms	Memory Size: 128 MB	Max Memory Used: 45 MB	Init Duration: 219.32 ms

Request ID
47124779-d771-4cdd-b6b7-c54ea9f29e80