# Angular


<p>  
    <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular Logo" height="260">
</p>

1. [Introduction](#introduction)
2. [Components, Core Directives and Pipes](#corecomponents)
3. [Local Templates Querying](#localtemplates)
4. [Content Projection](#projectionindepth)
5. [Templates](#templatesindepth)
6. [Directives](#directivesindepth)
7. [View Encapsulation](#encapsulation)
8. [Injectable Services](#injectableservices)
9. [Dependency Injection](#dependencyinjection)
10. [Change Detection](#changedetection)
11. [Lifecycle Hooks](#lifecyclehooks)
12. [Modules](#modules)
13. [Pipes](#pipes)
14. [Internationalization](#i18n)
15. [Elements](#elements)
16. [StandAlone Components](#standalonecomponents)

# Introduction
- Open source 
- Web application framework
- Maintained by Googlr
- used for building dynamic, single-page web application
- Set of tools for creating Everything
### features
- Component based architecture
- Templates
- Directives
- Dependency Injection
- Services
- Routing
- Obeservables
- Forms
- HttpClient
- Testing (Jasmine)
- Internationalization (i18n)
- CLI (command line interface)
### Installation
- Installing Node.js

```sh
sudo apt-get update
sudo apt-get install -y ca-certificates curl gnupg
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
```

```sh
NODE_MAJOR=20
echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list
```

```sh
sudo apt-get update
sudo apt-get install nodejs -y
```

    - Note : Make sure before installing Angular, you have installed Node.js on your machine
    
- Installing Angular
```js
npm i --global @angular/cli
``` 
### Creating first Application
- `ng new application_name` using this command you can create new application. 
```ts
ng new helloWorldApp
```
- Running app 
Using `ng serve` you can start angular application. Path will be where application located.
```ts
ng serve
```

# Components, Core Directives and Pipes

# Local Templates Querying

# Content Projection

# Templates

# Directives

# View Encapsulation

# Injectable Services

# Dependency Injection

# Change Detection

# Lifecycle Hooks

# Modules

# Pipes

# Internationalization

# Elements

# Standalone Components
