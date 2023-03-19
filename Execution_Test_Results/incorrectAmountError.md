Test Event Name
incorrectAmountError

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
START RequestId: 5050c565-b5da-4273-8ee4-7c45159589a9 Version: $LATEST
END RequestId: 5050c565-b5da-4273-8ee4-7c45159589a9
REPORT RequestId: 5050c565-b5da-4273-8ee4-7c45159589a9	Duration: 1.52 ms	Billed Duration: 2 ms	Memory Size: 128 MB	Max Memory Used: 46 MB

Request ID
5050c565-b5da-4273-8ee4-7c45159589a9