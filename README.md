[You do not know english](languages.md)

# simple html template

Just clone and edit without settings or extra installations.

A simple template to create simple statics web pages, which can work without internet, without frameworks and without any server-side applications such as Apache, Nginx or other similar, or at least with the minimum of them.

Also, this is made for those who are just starting out, they may have something to start with a structured project.


## contents
- [Application tree](#application-tree)
- [How to contribute to this repository?](#how-to-contribute-to-this-repository)
- [License](#license)
- [F.A.Q](#faq)


<a name="application-tree"/> 

### Application tree

```
root 
├── buildTasks
├── dist
├── docs
│   ├── _assets
│   └── es
│       └── _assets
├── src
│   ├── __libs
│   │   ├── lib1
│   │   └── lib2
│   ├── _commons
│   │   ├── css
│   │   ├── fonts
│   │   ├── img
│   │   └── js
│   │       ├── menu
│   │       ├── strings
│   │       │   └── es.js 
│   │       ├── external-routes.js
│   │       ├── images.js
│   │       ├── internal-routes.js
│   │       ├── PageLoader.js
│   │       ├── referencesIds.js
│   │       └── strings.js
│   ├── home
│   │   ├── css
│   │   ├── fonts
│   │   ├── img
│   │   ├── js
│   │   │   ├── menu
│   │   │   ├── strings
│   │   │   │   └── es.js 
│   │   │   ├── external-routes.js
│   │   │   ├── images.js
│   │   │   ├── internal-routes.js
│   │   │   ├── referencesIds.js
│   │   │   └── strings.js
│   │   ├── home.js
│   │   └── index.html 
│   │
│   ├── page1
│   │   ├── css
│   │   ├── fonts
│   │   ├── img
│   │   ├── js
│   │   │   ├── menu
│   │   │   ├── strings
│   │   │   │   └── es.js 
│   │   │   ├── external-routes.js
│   │   │   ├── images.js
│   │   │   ├── internal-routes.js
│   │   │   ├── referencesIds.js
│   │   │   └── strings.js
│   │   ├── page1.js
│   │   └── index.html 
│   │
│   └── page2
│       ├── css
│       ├── fonts
│       ├── img
│       ├── js
│       │   ├── menu
│       │   ├── strings
│       │   │   └── es.js 
│       │   ├── external-routes.js
│       │   ├── images.js
│       │   ├── internal-routes.js
│       │   ├── referencesIds.js
│       │   └── strings.js
│       ├── page2.js
│       └── index.html 
│
├── test
│   ├── buildTasks
│   │   ├── instrument
│   │   └── unit
│   └── src
│       ├── instrument
│       └── unit
├── index.html
└── main-index.js
```

<a name="how-to-contribute-to-this-repository"/>

### How to contribute to this repository?

Do you want to help us? Excellent! Take a look at the [guidelines](CONTRIBUTING.md) to follow to be able to make a pull request to this repository.

<a name="license"/>

### Licence
All files in this repository are licensed under the **MIT No Attribution** license. See more license details [here](LICENSE).

<a name="faq"/>

### F.A.Q

Why don't you use import in the .js files?

Because it that requires a server-side application, Also, it is a Issue for the type of `file:///` URLs. [More information about JavaScript's modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules#other_differences_between_modules_and_standard_scripts) 