# TCET Website
**Info:**
**The TCET official page is built using AstroJS, an all-in-one web framework designed for speed.**


### Steps to run the site on your local system: 
These are the steps you need to follow to get this site on your local system.

### Install Git in your computer
Follow these steps to install git in your computer.
1. Go to [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Click on Windows. Download should start.
3. Go to downloads and install the package.

### Clone the repo
Open Git Bash in any folder and paste the following command

> If you are making an external contribution its a good practice to first Fork & then clone the forked repo

```bash
git clone https://github.com/tcet-opensource/tcet-website
```

### Install NodeJS

1. Go to [https://nodejs.org/en/download](https://nodejs.org/en/download)
2. Select <b>Current</b>.
3. Download the 64-bit .msi version. Follow the steps and install NodeJS.

**Note:**
**It is important to have NodeJS in your system**

### Open the folder in VS Code
1. Install [VS Code](https://code.visualstudio.com/docs/?dv=win32user) if not installed. 
2. Open Windows Terminal in the folder you have cloned the repo, as done in [step 2](#clone-the-repo).

### Install Important Packages/Dependencies

Install yarn globally 

```bash
npm install -g yarn
```

You can make changes to your respective files and changes will be shown once you have saved the file.

### Commands used to run locally 

1. To run the commands, make sure that you have installed yarn globally first.
2. All commands are run from the root of the project, from a terminal

Here are a set of commands used to run locally:

| **Command** | **Action** |
| -------- | -------- |
| `yarn`   | Installs dependencies |
| `yarn dev` | Starts local dev server at `localhost:3000` |
| `yarn build` | Build your production site to `./dist/` |
| `yarn preview` | Preview your build locally, before deploying |
| `yarn astro ...` | Run CLI commands like `astro add`, `astro check` |
| `yarn astro --help` | Get help using the Astro CLI |

### Steps to run after a Pull / Merge: 

1. To install all dependencies

```bash
yarn
```
2. To run local dev environment

```bash
yarn dev
```

+ [x] make sure you PR on the Staging Branch

