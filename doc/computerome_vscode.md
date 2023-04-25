# VS Code on Computerome

VS Code is a free, open-source, cross-platform code editor developed by Microsoft. It is a very popular editor among developers, and it is also used by many researchers. Here is a guide on how to install and use VS Code on Computerome.

1. Open a virtual desktop session by ThinLinc
2. Download and install VS Code
   * Download [VS Code](https://code.visualstudio.com/sha/download?build=stable&os=linux-x64)
   * Extract the downloaded file (tar.gz) by running `tar -xvzf <filename>`
3. Test VS Code by running `./code` in the extracted folder. Often, you will get an error message. You could add `./code --no-sandbox` to the command to run VS Code without sandboxing.
4. You can add the following line to your `.bashrc` file:
   * `alias code='./path/to/code --no-sandbox'`
