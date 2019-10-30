# Creating Resume and README on GitHub
This README is going to explain how to use Git Flavored Markdown and Jekyll to edit a resume and host it on GitHub Pages.
## Audience
This READEME is targeted at people with some background knowledge about Atom IDE and Github. Also, this README is targeted to people with no experience in Markdown and no experience in Jekyll.
## Prerequisites
### Step1: Installation
1. Install a text editor (in this case we are using Atom)
  * Install Atom IDE using this link: [https://flight-manual.atom.io/getting-started/sections/installing-atom/](https://flight-manual.atom.io/getting-started/sections/installing-atom/).

### Step2: Configuration
1. Open a new repository on your GitHub Pages account
  + Click on the **New** button ![New Button](https://github.com/Annasisa01/IsaAnnas.github.io/blob/master/img/image1.15.15%20PM.png)
2. Connect/Clone GitHub repository to Atom IDE.
  + Click on the **Clone or download** button to copy the link to the repository ![Clone or download button](https://github.com/Annasisa01/IsaAnnas.github.io/blob/master/img/Image2.png)
    - Copy using `Clipboard button` or,  
    - Copy using: `Cmd + C`
  + Open your Atom.
  + Use `Cmd + Shift + P` to toggle Atom's Command Palette
  + Type `Clone` in the Command Palette and Click `return`
  + Paste the link to the repository in the panel that opens and then click `return`
    - Paste using `Cmd + V` or,  
    - Right click in the panel and then select `"Paste"`

## Instruction (Operations)
1. Create an index.md file inside the Git directory folder you just cloned.
2. Edit your resume using Markdown inside the index.md file.
  * **New to Markdown?** Get a quick Markdown tutorial from this [link!](https://helloacm.com/markdown-markup-language-quick-tutorial/)
3. Create a README.md too if one does not exist already.
4. Edit your README file using Markdown inside the README.md file.
   * Here are some guidelines for writing README files ![Guidelines for writing README](https://github.com/Annasisa01/IsaAnnas.github.io/blob/master/img/image3.png)
    * Check out an example of a README file [here!](https://github.com/alichtman/stronghold#readme)
5. Save files using `Cmd + S`.
6. Send/Push your files from your Atom IDE to your hosted GitHub repository.
  + Open Git tab.
    - Click on **Packages** in your toolsbar.
    - Select **Toggle Git Tab** under GitHub.
  + Click on **Stage All** in the Git Tab.
  + Type a commit message inside the text box provided.
  +  Click on `Commit to master`
  + Click on the `Push` button at the bottom of the page.
7. Apply/Change theme.
  + Go to your github pages profile.
  + Click on settings.
  + Scroll down and select the `Change theme` button.
    - This would take you to a page where you can select a theme of your choice.
    - Once you have chosen a theme, a `_config.yml` file would be added to your repository.
8. Change the title in your hosted resume.
  + Open the` _config.yml` file.
  + Add a new line `title: Resume for [Your name]`
  + Click on the `Commit Changes` button.
## More resources
* Still having problems with installing Atom? Watch a tutorial on how to install Atom ![here](https://www.youtube.com/watch?v=wrKiC3CceYg)
* Still having problems connecting your GitHub repository with Atom? Watch a tutorial ![here](https://www.youtube.com/watch?v=7Id1_VfbEKo)
## FAQs
somEthing.
## License
View [Permit](https://github.com/Annasisa01/IsaAnnas.github.io/blob/master/license/license.md)
## Credits and Acknowledgement
  * Uklein Anton and Ezzahir Chris for consultation and help with syntax.  
  * 3040 Course resources by Christina Penner were very helpful in this project.
