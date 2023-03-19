Test Event Name
correctDialog

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
START RequestId: d149d696-b743-46ee-ae12-3c87432281b1 Version: $LATEST
END RequestId: d149d696-b743-46ee-ae12-3c87432281b1
REPORT RequestId: d149d696-b743-46ee-ae12-3c87432281b1	Duration: 1.59 ms	Billed Duration: 2 ms	Memory Size: 128 MB	Max Memory Used: 45 MB

Request ID
d149d696-b743-46ee-ae12-3c87432281b1