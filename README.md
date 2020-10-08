# :boom: rocket-webapp-components

![Core](core_components/src/assets/img/rocket-components-small.png)


An open-source and community-driven project to provide a consistent user interface across web applications. 
Ensuring a consistent look and feel, while harmonizing multiple products and applications, is a demanding and expensive task.
Therefore, our set of libraries cover the most common UI components (Material-UI component wrappers), patterns and layouts. 
It offers a design system and component library that allows teams the flexibility to quickly implement consistent UX, without needing to change the frontend framework or library. :sunglasses:

Key features:
- modularity: revolves around self-contained components, while encapsulating theme styles and behaviors
- flexibility: designed around theming capabilities, combines basic blocks to create complex components
- collaborative: contributors are welcomed, the bigger the community, the faster the releases cycles will be


## Installation
Bit components are stored on the bit registry located in https://bit.dev/totalsoft/react-mui.
When installing @bit component with npm or yarn, they will try to install the components starting with @bit by resolving the @bit registry. This configuration is stored in an .npmrc configuration file.

First add a new `.npmrc` file in your project, if not exists, containing the following:

```shell
@bit:registry=https://node.bit.dev
//node.bit.dev/:_authToken=${BIT_TOKEN}
always-auth=true
```

> the always-auth=true is required when using Yarn. It is not required
> for npm.
  
```bash  
npm i @bit/totalsoft.react-mui.core
```  

Check-out this video to see how to install this library and some info about BIT_TOKEN: [Instalation and what is BIT_TOKEN](https://1drv.ms/v/s!AjNJY058hJ8vgRNx60Iq0ZJh0CR3?e=ak6waj).


## Leverage Bit CLI by using Azure DevOps

#### The best approach of working with the core of components
Bit platform comes with a performant CLI with which you can import, tag, and export components. (Of course, there are a lot of commands but for the sake of our purpose those three are enough). To work with components you are not supposed to have prior experience with Bit because Azure DevOps do that for you. But how? To answer, by pipeline steps we set in which there are certain commands for exporting and tagging components. You just have to do some changes in your components and set up a pull request. Afterward, the pipeline will carry your changes on Bit.

Please, take a look at this video for further understanding of these steps: [Working with Azure Pipeline](https://1drv.ms/v/s!AjNJY058hJ8vgRSKSG8XfBMoXbU8?e=3VFY19)

  
 ##  Bit in a nutshell
![BitWorkflow](core_components/src/assets/img/BitWorkflow.png)

Bit is an open-source CLI tool for collaborating on isolated components across projects and repositories.

Use Bit to distribute discrete components from a design library or a project into a standalone reusable package and utilize it across applications.

You can set up your own server for components collaboration, or use the bit.dev cloud hosting for private and public components sharing.

Bit facilitates the process of collaborating on UI components. Team members can share, maintain, and synchronize isolated components from different projects.

Bit allows teams to:

 - Increase code reusability
  - Increase design and development efficiency
   - Retain UI and UX consistency
   - Increase project's stability

  

Key Features:

- Extract a component for sharing directly from an existing library or project.
- Validate the component's independence by building and testing each component separately from the rest of the project.
- Change the source code of shared components from any application that utilizes it.
- Get published changes in components on top of local modifications.
- Contribute back changes made to components directly from the consuming applications.
- Automatically wrap each component as an npm package.
- Distribute discrete components instead of a single massive package.
- Automate component versioning according to changes in its dependencies.
- Use with leading frameworks and tools: React, Vue, Angular, Mocha, Jest.

Bit works alongside Git, NPM, and Yarn.
Check out https://docs.bit.dev/docs/quick-start for further information about Bit.

## Our Bit account

We have an account where we place all the components written in React gathered in a single package named _**core**_.

You should check out the following link https://bit.dev/totalsoft/react-mui/core, where you can see a lot of helpful information about the package, such as:

- the current version(with all the old versions along)
- the number of downloads
- the latest changes
- the description
- the providers which you can import the package with
- the overview of the package where you can test and write some code to see how it behave
- the dependencies
- the output of the build

Please, listen to this video to better comprehend all of the aforementioned sayings: [Bit info](https://1drv.ms/v/s!AjNJY058hJ8vgRKCFjagQvoBKuXO?e=AWkXMv)

