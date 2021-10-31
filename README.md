# Visualforce Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

- Run `npm install` in root of project to install useful scripting plugins.
- Run `sfdx force:user:password:generate -l 6 -c 2` to generate a password for your scratch org user. 

## Importing Test Data

- Use the [Texei SFDX Plugin](https://github.com/texei/texei-sfdx-plugin)
- Test data exists in `/data` folder
- Open terminal to root of the repo
- Type `sfdx texei:data:import --inputdir ./data`

## Create scratch org from VS Code

- `Ctrl+Shift+P` and `SFDX: Create a Default Scratch Org...`

## Other Useful Tools

- [Mockaroo](https://mockaroo.com/) - Fake data generation.
- https://dataloader.io - Import data into your scratch org.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Visualforce Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.234.0.pages.meta/pages/pages_intro.htm)
- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
