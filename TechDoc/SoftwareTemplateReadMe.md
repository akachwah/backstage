# Red Hat Developer Hub Software Templates 

## Welcome to Templates

Welcome to the Red Hat Developer Hub Software Templates Repository. This repository contains a collection of software templates designed to illustrate best practices in software development and deployment. Our templates cover a wide range of technologies and frameworks, ensuring you have a suitable starting point for your project's needs.

## Overview

### Software / Golden Templates

Software / Golden Templates are pre-configured, best practice templates that are considered the standard for certain types of applications or environments. They are maintained with the latest recommendations and practices. Using Software Templates can help ensure that your projects adhere to industry standards and organizational policies.


Our software templates are crafted to provide you with a solid foundation for your projects. Each template is a blueprint that includes predefined configurations, dependencies, and deployment procedures. These templates are intended to help you quickly set up and deploy applications with industry best practices.


## Disclaimer

The software templates provided in this repository are examples meant to serve as a starting point. Users are strongly encouraged to customize and modify these templates to fit their specific project requirements and organizational standards. 

By using these templates, you agree to do so at your own risk and discretion. Red Hat shall not be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of these templates, even if advised of the possibility of such damage.

### Customization

Each template in this repository is designed with adaptability in mind, allowing for easy adjustments in configuration, dependencies, and deployment procedures. We strongly encourage users to:

*    Modify templates to suit their specific project requirements.
*    Adjust configurations to align with organizational standards.
*    Adapt deployment procedures to fit their unique environments.

Please note that all templates are unsupported and unmaintained. Users should adapt them for their needs and use them at their own risk.

## Getting Started

Be sure to have covered [Getting Started with Developer Hub](https://developers.redhat.com/rhdh/getting-started) before proceeding. The Software Templates are available under /create. 

Once there, you should see something that looks similar to this:

![Create](./Create.png)



### Choose a template

When you select a template that you want to create, you'll be taken to the next page which may or may not look different for each template. Each template can ask for different input variables, and they are then passed to the templater internally.

![Create](./Create-2.png)

### Run!

Once you've entered values and confirmed, you'll then get a page with live progress of what is currently happening with the creation of your template. It shouldn't take too long, and you'll have a success screen!

![Create](./Create-3.png)

If it fails, you'll be able to click on each section to get the log from the step that failed which can be helpful in debugging.

You can also cancel the running process. Once you clicked on button "Cancel", the abort signal will be sent to a task and all next steps won't be executed. The current step will be cancelled only if it supports it.

![Create](./Create-4.png)


### View Component in Catalog
When it's been created, you'll see the View in Catalog button, which will take you to the registered component in the catalog:

![Create](./Catalog.png) 

