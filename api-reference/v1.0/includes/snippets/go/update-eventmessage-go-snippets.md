---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewMessage()
isRead := true
requestBody.SetIsRead(&isRead)
messageId := "message-id"
graphClient.Me().MessagesById(&messageId).Patch(requestBody)


```