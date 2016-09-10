This directory contains the code for the "Function app" **testfunction16**.

The folders are the functions within the functions app.

The function *HttpTriggerCSharp1* has the URL [https://testfunction16.azurewebsites.net/api/HttpTriggerCSharp1]().

Note that by default functions require the API key to be send in the request, either via `x-functions-key` HTTP header, or via `code` URL parameter. The API key, as well as master and function keys are located in the `D:\home\data\Functions\secrets` folder in the file system of the function app. You can use "Kudu" in "Function app settings" to view and manipulate files of the function app.