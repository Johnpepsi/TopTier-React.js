# TopTier-React.js
This repository contains all my mistakes and learning through the process of learning reactJS such as running it through the server, by utilizing the correct scripting, etc.

## What does Package JSON do?
- `package.json` is a file commonly found at the root of a Node.js project directory. It serves several critical functions:
- Project Metadata: It contains metadata relevant to the project, such as the project's name, version, description, author, license information, and more.
- Dependency Management: It lists all the dependencies (libraries, frameworks, tools) required by the project under dependencies and devDependencies. When you run npm install,
- Node's package manager (npm) automatically installs the versions of the packages specified in these fields.
- Version Control: It locks down the versions of installed packages to ensure that the project is consistent and works across different environments. This is often managed by an accompanying file called package-lock.json or yarn.lock if Yarn is used.

# What error may I face when Running ReactJS in the local server?
1. The error you could encountering, `"ENOENT"`. It is is a common error code in Node.js and in many other POSIX-compliant operating systems. The ENOENT stands for "Error NO ENTry" or "Error NO ENTity". In this context, it indicates that the required
2. `"react-scripts' is not recognized as an internal or external command, operable program or batch file."` The error message for example "react-scripts is not recognized as an internal or external command, operable program or batch file" suggests that the react-scripts package is not installed in your project, or there is a problem with your Node.js environment path configuration.
3. `"Compiled with problems:"` The errors you're encountering are indicating that the webpack build process is unable to find and import the modules specified in your files. 
