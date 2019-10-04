#Cloud Formations

## Lab 43
### Process
* run `npx create-react-app cool-react-app` to initialize a React app.
* upload this to a GitHub repo
* create a GitHub token on your github page
  * click on your user image (top right corner of page)
  * choose `settings`
  * choose `developer settings`
  * choose `personal access tokens`
  * choose `generate new token`
    * give it a name and generate the token

### Images

* Create the stack:
  * choose `Template is ready`
  * choose `Upload a template file`
  * upload the yml file

![create stack](./assets/create-stack.png)

* Configure the stack:
  * leave all values as default

![configure stack](./assets/configure-stack.png)

* Stack Details:
  * add a unique name to the stack

![stack details](./assets/stack-details.png)

* Stack List:
  * this shows all created stacks

![stack list](./assets/stacks.png)

* Stack Overview:
  * provides details about the stack

![stack overview](./assets/stack-overview.png)

## Lab 44
### Template 1
* Need to change all instances of the `cool-react-bucket` from kebab-case to camelCase.
