# Introduction

Here we will locally a basic .net Function, which will copy an uploaded blob from a container named `data` to a container named `newdata`

![]()

## Steps

- First, modify the `local.settings.json` and add the storage account connection string accordingly:

![]()

- You can get the connection on `Access keys` in Azure Portal:

![]()

- Run the function:

![]()

- Upload a file to the storage account, remember to set the container name on the task;

- The function detects the uploaded blob and then uploads a copy to another container called `newdata`.

![]()

>`logs`

![]()

>`storage account containers`

>The containers `azure-webjobs-hosts` and `azure-webjobs-secrets` are being used by Visual studio.