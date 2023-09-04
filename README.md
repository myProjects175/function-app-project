# Introduction

Here we will locally a basic .net Function, which will copy an uploaded blob to a container.

![]()

## Steps

- First, modify the `local.settings.json` and add the storage account connection string accordingly:

![]()

- You can get the connection on `Access keys` in Azure Portal:

![]()

- Run the function and upload a file to the storage account, remember to set the container name on the task;

- The function detects the uploaded blob and then uploads a copy to another container called `newdata`.

![]()