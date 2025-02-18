**Windows Users**

1. Open R Studio and check your version of R. The top of the Console window area should display the version of R at startup.
   1. Using up-to-date version of R (or at least 4.3+) is highly recommended for compatibility
   2. Most recent version of R can be installed from the [CRAN website](https://cran.r-project.org/)
2. Close R Studio
3. Go to this [link](https://cran.r-project.org/bin/windows/Rtools/) and check then find the appropriate version of RTools that corresponds to your R version.
   1. For Rtools 4.2 and higher, download the Rtools installer and install using the installer
   2. For RTools 4.0 or lower, you may need to perform one more step of putting the location of the Rtools make utilities on the PATH variable. The detailed instructions are available at the bottom of [this page](https://cran.r-project.org/bin/windows/Rtools/rtools40.html). Again, this is only necessary if you wish to install RTools 4.0 or lower

**Mac Users**

If you're not developing software for an Apple device you do not need full Xcode application (which is large). You only need to install Xcode Command Line Tools.

Apple made it easy  to install Xcode Command Line Tools by having certain commands prompt you to begin installation.

Running any of these commands in the Terminal will trigger a prompt to install Xcode Command Line Tools:

- `clang` - a compiler that turns source code into an executable program
- `gcc` - GNU compiler
- `git` - version control system

Another option is to enter `xcode-select --install` in the terminal to begin installation process.

Once you have finished installation, try opening another terminal and run `xcode-select -p` to verify the installation is successfully completed.

Another method is to use Homebrew. Detailed instruction for this approach is available [in this page](https://www.freecodecamp.org/news/install-xcode-command-line-tools/).

**Additional Support**

If you run into any problems, feel free to reach out to us by requesting [a consultation](bit.ly/rcdsconsult)


