# NodeGuiDemo

## Setup
*(Instructions provided from https://react.nodegui.org/docs/guides/getting-started/)*

### Requirements:
* Visual studio 2017 and up.
* CMake 3.1 and up *(Download can be found here: https://cmake.org/download/)*
    * Download the latest Windows X64 zip folder from binary distributions  
    * Open a command prompt window in administrator mode 
    * Type chocolatey install cmake
* Currently supported Node.Js versions are 12.x and up.
* We strongly suggest you use some kind of version manager for Node.Js. This would allow you to switch to any version of nodejs quite easily. We recommend nvm: https://github.com/nvm-sh/nvm
* We strongly recommend Powershell as preferred terminal in Windows.

### Confirm that both node, npm, and cmake are available by running:
* This command should print the version of Node.js:
        node -v
* This command should print the version of npm:
        npm -v
* This command should print the options within cmake:
        cmake
* If all commands printed something out, you are all set! Before you get started, you might want to install a code editor suited for JavaScript development.

### Recommended Editor and Setup:
* For this project We will use Microsoft's Visual Studio Code.

* Follow plugin setup suggestions for the VS Code in the doc: 
    *Documentation\Plugin Suggestions\Visual Studio Code Plugin Suggestions.docx*

If you are one of the many developers with a strong preference, know that virtually all code editors and IDEs these days support JavaScript.

### Creating the initial Application:
* Clone and run the code in this tutorial by using the nodegui/react-nodegui-starter repository.
    *Note: Running this requires Git and npm.*

* Clone the repository:
    $ git clone https://github.com/nodegui/react-nodegui-starter
* Go into the repository:
    $ cd react-nodegui-starter
* Install dependencies *(This will install the latest updates from NodeGUI)*:
    $ npm i http://master-release.nodegui.org
* Run the dev server:
    $ npm run dev
* Run the app on a separate terminal tab or window:
    $ npm start

**That's it!**

**Congratulations! You've successfully run and modified your first React NodeGui app.**
