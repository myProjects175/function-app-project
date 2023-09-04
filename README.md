# Introduction

Here we will locally a basic .net Function, which will copy an uploaded blob from a container named `data` to a container named `newdata`

![](https://github.com/nokorinotsubasa/function-app-project/blob/5dcdb0001dfe4a1eeb953b181c26e2e31651309c/images/Architecture.png)

## Steps

- First, modify the `local.settings.json` and add the storage account connection string accordingly:

![](https://github.com/nokorinotsubasa/function-app-project/blob/5dcdb0001dfe4a1eeb953b181c26e2e31651309c/images/localsettingsjson.png)

- You can get the connection on `Access keys` in Azure Portal:

![](https://github.com/nokorinotsubasa/function-app-project/blob/5dcdb0001dfe4a1eeb953b181c26e2e31651309c/images/AccessKeys.png)

- Run the function:

![](https://github.com/nokorinotsubasa/function-app-project/blob/5dcdb0001dfe4a1eeb953b181c26e2e31651309c/images/functionwaiting.png)

- Upload a file to the storage account, remember to set the container name on the task on the code;

- The function detects the uploaded blob and then uploads a copy to another container called `newdata`.

![](https://github.com/nokorinotsubasa/function-app-project/blob/5dcdb0001dfe4a1eeb953b181c26e2e31651309c/images/functionlogs.png)

>`logs`

![](https://github.com/nokorinotsubasa/function-app-project/blob/5dcdb0001dfe4a1eeb953b181c26e2e31651309c/images/containers.png)

>`storage account containers`

>The containers `azure-webjobs-hosts` and `azure-webjobs-secrets` are being used by Visual studio.