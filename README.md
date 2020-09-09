# ServerlessBot

Serverless Bot using Azure Serverless &amp; Github actions

## Steps

- Install Visual Studio Code
- Install Azure Functions plug-in
- Download & install from https://github.com/Azure/azure-functions-core-tools#installing
- Add folder extracted from the ZIP downloaded above to PATH environment variable.
- Add following setting in `~/.config/Code - OSS/User/settings.json`:

   ```json
   "terminal.integrated.env.linux": {
        "PATH": "./:/home/rasin/.nvm/versions/node/v12.18.3/bin:/home/rasin/work/softwares/azureFunctionsCli/:/home/rasin/.local/bin:/usr/local/bin:/usr/bin:/bin:/usr/local/sbin:/usr/bin/site_perl:/usr/bin/vendor_perl:/usr/bin/core_perl"
    }
    ```

- Install nodeJS & npm: <https://dev.to/lobo_tuerto/how-to-install-nodejs-in-manjaro-linux--5ha4>
- If VS code gives error for missing Azure functions core tools, skip it as shown in https://github.com/microsoft/vscode-azurefunctions/issues/2140
  - Set `azureFunctions.validateFuncCoreTools` to False
- 

## References:

- https://www.youtube.com/watch?v=oxHSC_n7Td8
