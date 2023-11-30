# **SharePoint Starter Prerequisites**

Here are the current pre-requirements for creating your first ever solution in SharePoint using SPFx.

- You will need to be a tenant administrator to be able to deploy the solution.

- Notice that you need to acquire the free developer tenant from [CDX Program](https://cdx.transform.microsoft.com/my-tenants).

&nbsp;

## **Required tools & libraries:**

| Tool Name | Version | Download |
| --- | ----------- | --- |
| Visual Studio Code | latest | [link](https://code.visualstudio.com/)
| Node.js | 16.18.1 | [link](https://nodejs.org/dist/v16.18.1/node-v16.18.1-x64.msi)
| Edge / Chrome | latest | -
| Powershell / Command Prompt  | latest | Available by default
| Git | latest | [link](https://git-scm.com/)
| Postman | latest | [link](https://www.postman.com/downloads/?utm_source=postman-home)

**Note:** Kindly avoid installing beta/alpha/dev channel versions for all the tools and libraries. Those versions may or may not work but they might be associated with bugs & are purely for previewing the upcoming changes that may or may not get added to the stable release.

&nbsp;

### **Required npm libraries:**

Once you have installed the above tools, get start with installing the below libraries. Open command prompt / powershell and run the below commands:

`npm install gulp-cli yo @microsoft/generator-sharepoint@1.16.1 --global`

**Note:** The above oneliner command installs all the necessary modules / libraries which are required for the SPFx project creation as well as running the solution.

&nbsp;

**Optional API Fetching Libraries:**
| Tool Name | Version | Link |
| --- | ----------- | --- |
| PnP JS | latest | [link](https://pnp.github.io/pnpjs/getting-started/) |
| MS Graph Client | latest | [link](https://www.npmjs.com/package/@microsoft/microsoft-graph-client) |

PnP JS configuration sample: [link](https://dev.azure.com/sandeepps/SharePoint%20Samples/_git/PnPV3-Sample)

&nbsp;

**UI Libraries:**
| Tool Name | Version | Link |
| --- | ----------- | --- |
| Fluent UI V9 | latest | [link](https://react.fluentui.dev/?path=/docs/concepts-developer-quick-start--page) |
| Fluent UI V8 | latest | [link](https://developer.microsoft.com/en-us/fluentui#/controls/web) |

&nbsp;

### **Creating a new solution:**

1. Create a folder for your project, navigate to that folder & open command prompt, run `yo` command.
![Alt text](image.png)
2. Press enter & choose the client-side component that you want to create.
![Alt text](image-1.png)
3. Suppose if I choose the webpart here I need to enter the webpart name and type of the template that I want to generate for example if I choose React, it will generate the files for React.
![Alt text](image-2.png)
&nbsp;

<center>

![Alt text](https://i.pinimg.com/originals/b2/32/55/b2325557a903fdf56b50da4656da9221.gif)
</center>

## <p style="text-align: center">**Happy Coding!</p>**
