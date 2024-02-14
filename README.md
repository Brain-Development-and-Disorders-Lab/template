# Repository Template

The template repository for code and data created and used by the Brain Development and Disorders Lab.

## Template Features

* **License**: All repositories will be shared under a *Attribution-NonCommercial-ShareAlike 4.0 International* license, included in this template.
* **Issue Templates**: A bug report issue template has been included.
* **Citation File**: A citation file has been included. This should be updated with appropriate details to ensure the repository is cited correctly.

The default branch name is `main`.

## Template Usage

To use the template, click the green *Use this template* button. This will prompt you to configure your new repository.

1. Set the owner to `Brain-Development-and-Disorders-Lab` from the drop-down menu. If you cannot set the organisation, make sure you are a member.

2. Set the name of the repository. If creating a repository for a publication, the naming standard is: `Author_etal_YYYY[_keywords]` where `keywords` is an optional set of keywords associated with the publication. Examples of repository names that use this standard:
    * `Smith_etal_2021`: code and data associated with John Smith's publication in 2021.
    * `Smith_etal_2021_cognition`: code and data associated with John Smith's publication in 2021 that examines cognition.

3. Provide a description of the repository. This should be about one sentence that concisely outlines what the code and data does and is associated with.

4. Set the repository visibility initially to `Private`.

5. Click `Create repository from template`, then proceed to add your files.

### Recommended configuration

* **Branch protection**: Branch protection should be enabled for the `main` branch. Only the code owners should be able to push to the `main` branch. The following rules are recommended to be enforced:
  * *Require a pull request before merging_
  * *Require status checks to pass before merging* (if status checks have been enabled)
  * *Include administrators*
* **GitHub Actions**: GitHub Actions should be disabled by default. They can be enabled if required.
* **GitHub Wikis**: GitHub Wikis should be disabled by default. Data and code documentation are included and versioned in the repository.
* **GitHub Projects**: Unless the repository is a work-in-progress, GitHub Projects should be disabled.

## Release Preparation

Before releasing code and data using this template, a number of steps should be taken to ensure the repository is adequately prepared.

1. Apply recommended security features such as branch protection after creating the repository from the template.

2. Create or update the `.gitignore` file. A `.gitignore` file allows files matching certain patterns to be excluded from version control. This is useful for projects that automatically create extra artefacts such as caches or temporary files. A `.gitignore` file has been included in this repository as a generic starting point.

3. Create or update the repository license. There are many licenses available for open-source projects. An appropriate license should be added to the repository.

4. Ensure all dependencies are correctly listed and up to date. This is of paramount importance if external packages are used or referenced throughout the code.

5. Update the `CITATION.cff` file with appropriate details.

6. Set the repository to `Public` visibility once all code and data has been added to the repository and checked.
    * An effective testing strategy is to clone the private repository into a fresh environment, and run through any steps you would normally take to run or verify the code and data.
    * If you are using tools that install or depend on packages such as R or Python, ensure you have tested installing all dependencies from Step 3, ideally in a fresh environment with a new installation of the language.

## License

<!-- CC BY-NC-SA 4.0 License -->
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
  <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" />
</a>
<br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Issues and Feedback

Please contact **Henry Burgess** <[henry.burgess@wustl.edu](mailto:henry.burgess@wustl.edu)> for all code-related issues and feedback.
