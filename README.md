# How to host a Resume on GitHub Pages

## Purpose

These instructions describe the steps to follow in order to host a resume and README on GitHub Pages. This will be accomplished by using a variety of tools and principles explored in Andrew Etter's book _Modern Technical Writing_. A link to Andrew Etter's book can be found in the "More Resources" section of this README.


## Prerequisites

Requirements for this tutorial is a working knowledge of Markdown. Additionally, a resume formatted in Markdown is also required to complete this guide. If you are inexperienced with Markdown, or would simply like to brush-up your skills, you may find the included Markdown tutorial helpful.

- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

## Instructions


### Creating a GitHub Pages account


  1. Click the following link to create a [GitHub](https://github.com/signup?user_email=&source=form-home-signup) account.

  2. Choose a GitHub username that reflects your preferred name. This is because which ever user name you choose will be apart of your site address.

  2. Sign into your GitHub account and select the green (create a) *NEW* (repository) button as shown below.

  ![Create a new repository](https://github.com/RyanDCampbell/RyanDCampbell.github.io/blob/366344cdce03e774a4f1f546f04dd6760714d090/images/CreateRepo.PNG)

  3. **WARNING:** When naming your new repository, make sure it is named *username*.github.io, where *username* is the GitHub account username you selected in step 2.

###  Installing Software

There are a few programs that you will need to have installed before we can host your resume on GitHub Pages. Namely, Atom, GitHub Desktop, RubyInstaller and Jekyll. .Ruby is required by Jekyll as a Prerequisite.. Lastly, Jekyll turns our Markdown formatted document and converts in into a static website that we will host on GitHub Pages.


#### 1) Installing Atom

 Atom is the Markdown editor we will be using for this guide. GitHub Desktop will be used to push the changes we make to our static site


  1. Click the following link to download and install [Atom](https://atom.io/).

  2. Run the Atom installer, and complete the installation with the default installation settings.



#### 2) Installing GitHub Desktop

GitHub Desktop is the software that we will be using to update our static site with the changes that have been made to the Markdown resume.  GitHub gives us some very useful tools as described in *Modern Technical Writing*. Two advantages of using GitHub is version control and community contributions.

 Version control gives us a way of tracking the changes that have been made to the project, and a way of restoring our project to a previous version.

 Community contributions embrace the benefits of open source. By publicly hosting projects, other GitHub community members can contribute to your project. They can suggest changes and fixes, helping you to add an extra layer of polish to your projects.

 1. Click the following link to download and install [GitHub Desktop](https://desktop.github.com/).

 2. Run the GitHub Desktop installer using the default installation settings.

 3. Enter your GitHub account user name and password to log into GitHub Desktop.



#### 3) Installing Ruby

  1. Click the following link to download and install [Ruby+Devkit](https://rubyinstaller.org/downloads/).

  2. Select the Ruby+Devkit 2.7.X (64) to download the installer, as it is the recommended version to use.

  3. Run the Ruby+Devkit installer when the download completes.

  4. Proceed through the installation process, using the default installation options.

  5. When the installation has completed, ensure that the checkbox is selected as in the following image.  

  ![Successful Ruby Install](https://github.com/RyanDCampbell/RyanDCampbell.github.io/blob/366344cdce03e774a4f1f546f04dd6760714d090/images/RubySetup.PNG)

  6. Select finish.

  7. Verify that Ruby was successfully installed by opening a command prompt window, and entering the following command:


    ruby -v


  If Ruby was successfully installed, you will get the following feedback from command prompt:

  ![Verify Ruby Installed](https://github.com/RyanDCampbell/RyanDCampbell.github.io/blob/366344cdce03e774a4f1f546f04dd6760714d090/images/VerifyRuby.PNG)




#### 4) Installing Jekyll

  1. Open a new command prompt window.

  2. Enter and run the following command:


    gem install jekyll bundler  



If Jekyll was successfully installed, you will get the following output to command prompt:

  ![Jekyll Installed](https://github.com/RyanDCampbell/RyanDCampbell.github.io/blob/366344cdce03e774a4f1f546f04dd6760714d090/images/JekyllInstalled.PNG)




####  2) More Resources:



- [GitHub Pages](https://pages.github.com/) - A link to GitHub Pages has the steps needed to create an account
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/) -  A very good guide to get you started in Markdown, or simply brush-up your skills.
- [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) - A link to Andrew Etter's book *Modern Technical Writing*.
- [Jekyll Quickstart Guide] (https://jekyllrb.com/docs/) - A link to Jekyll's guide on how to get their software up and running.




## Built With
  - [Atom](https://atom.io/) - Used as a Markdown editor.
  - [GitHub Pages](https://pages.github.com/) - Used to host the static site.
  - [Jekyll](https://jekyllrb.com/) - Used for generating a static site from a Markdown file.
  - [Contributor Covenant](https://www.contributor-covenant.org/) - Used
for the Code of Conduct
  - [Creative Commons](https://creativecommons.org/) - Used to choose
    the license

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code
of conduct, and the process for submitting pull requests to us.


## Authors & Acknowledgments
- **Ryan Campbell** - *Wrote the guide on how to host a resume and README on GitHub Pages* -
- **Kevin Kim** - *Provided support on getting Jekyll and GitHub Pages setup. Also peer reviewed this guide* -
- **Joshua Moreira** - *Peer reviewed this guide* -
- **Ikram Khan Shipon** - *Peer reviewed this guide* -
- **Anton Sikorsky** - *Peer reviewed this guide* -
- **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in the README template project.

## FAQs

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this
repository](https://github.com/PurpleBooth/a-good-readme-template/tags).


## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details
