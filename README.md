# fm-red

FileMaker + Node-RED

### About

This repository acts a basic "getting started" guide for the new-to-Node-RED FileMaker developer.

### Prerequisites

Before installing this package, make sure you have Node.js installed. If you do not have Node.js installed, visit the <a href="https://nodejs.dev/download/">Node.js downloads page</a>.

This project requires Node-RED to be installed globally on the machine. If you do not have Node-RED installed, check out the <a href="https://nodered.org/docs/getting-started/local#installing-with-npm">Installing with npm</a> portion of the <a href="https://nodered.org/docs/getting-started/">Getting Started Page</a>.

This project makes use of the `node-red-contrib-filemaker` package. Please <a href="https://flows.nodered.org/node/node-red-contrib-filemaker">install this package</a> before cloning the repository.

### Installation

To clone this repository locally on your machine, open your terminal and type:

```bash
git clone https://github.com/softwarethatfits/fm-red.git && cd fm-red #This will clone and enter into the project
```

Next, install the needed dependencies with npm:

```bash
npm install #This will install any needed dependencies inside the project folder
```

Next, start up node red with:

```bash
node-red #This will boot up Node-RED
```

### Loading the `flow.json` project file

If Node-RED does not automatically import the `flow.json` file contained in the `./fm-red` folder, import the file from the Node-RED workspace using the hamburger menu (three horizontal bars stacked) in the top-right corner of the workspace: `Import > select a file to import > (navigate to the fm-red folder you cloned) > flow.json > Upload`.

### 🎉 Complete!

Way to go, you're all set up!

### Helpful Links

- <a href="https://www.youtube.com/watch?v=NAxhuWRsZWw">FileMaker and Node-RED Demo (Claris Devcon Presentation)</a>
- <a href="https://flows.nodered.org/">Node-RED Library</a>
- <a href="https://flows.nodered.org/node/node-red-contrib-filemaker/">`node-red-contrib-filemaker` package</a>
- <a href="https://mossrock.com/intro-to-curl-filemaker/">Intro to cURL and FileMaker</a>
# fm-red
