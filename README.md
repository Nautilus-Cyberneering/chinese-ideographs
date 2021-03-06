# Chinese Ideographs

[![Gold Drawings Processing](https://github.com/Nautilus-Cyberneering/chinese-ideographs/actions/workflows/gold-drawings-processing.yml/badge.svg)](https://github.com/Nautilus-Cyberneering/chinese-ideographs/actions/workflows/gold-drawings-processing.yml) [![MegaLinter](https://github.com/Nautilus-Cyberneering/chinese-ideographs/actions/workflows/mega-linter.yml/badge.svg)](https://github.com/Nautilus-Cyberneering/chinese-ideographs/actions/workflows/mega-linter.yml)

## Content

- [Project Description](#project-description)
- [Project Documentation](#project-documentation)

---

## Project Description

***Ethical Software Artwork Management Continuous Integration Workflow for a Website, Book and Game***

### Need

Developing large and complex digital tools requires software development skills making it difficult for artists to contribute without these. Also, the more humans are involved in any project, the easier errors are generated.We need to generate a repository structure and automated continuous workflow to handle a large media database made up of images, sound and video, which can be expanded and updated easily with a minimum level of technical skills and human intervention in the process of website population, book generation and game creation by different contributor teams.

### Approach

We will develop a continuous integration workflow that automatically manipulates and transforms large media files such as large high-resolution images, and associates necessary metadata and text content in bulk or individually and integrates these in the website, book and game.

(future) We need to have a polished workflow with supporting tools (such as a GUI application for the desktop computers, or at least a plugin for a good GIT GUI), that will help manage the process of updating and creating a pull request for the artists.

### Technical details

The image validation and processing is done using [Nautilus Librarian](https://github.com/Nautilus-Cyberneering/nautilus-librarian), a console application to handle image libraries.

This librarian will perform those general task on each one of the new images uploaded to the repository:

- Validate its path and filename
- Generate the base images
- Commit the new base images to the repository

This process is done in a Github actions workflow that is triggered when a new Pull Request with a Gold Image operation is created.

### Benefit

Reducing the impact of human intervention, eliminating human errors and creating consistency as well as time savings in a project that is expected to grow with time as more and more media is generated for either three of the final products.

Allows artists not to depend on developers to grow the final products.

Ethical Software Limited can focus on the creation of quality media.
Ethical Software Limited can audit and review their media to verify its quality. Both at the stage of proposal (pull requests), and after merged.
Over time this public process allows outside contributors to participate in the review process and eventually also contribute quality media.

Consumers will always have access to free and updated resources as soon as new media are generated and added to the database.

### Competition and Market solutions

In the digital world, there exist different Chinese language learning sites in addition to online dictionaries, games, etc. but none with an automated continuous integration workflow for their media.

### Collaboration with

This project is done in close collaboration with:

Ethical Software Ltd. (Hong Kong)
<https://www.ethicalsoftware.hk/>

All images in this repository are images supplied by Ethical Software Ltd.
This content by Ethical Software is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/). Please take some time and read their [Privacy Policy](https://www.ethicalsoftware.hk/?page_id=3).

## Project Documentation

- [Contributing](CONTRIBUTING.md)
- [Contributor Code of Conduct](documentation/Contributor_Code_of_Conduct.md)
- [File Naming Convention](documentation/File_Naming_Convention.md)
- [Filenames and Folder Structure Conventions](documentation/Filenames_and_Folder_Structure_Conventions.md)
- [Gold Images](documentation/Gold_Images.md)
- [Governance](documentation/Governance.md)
- [Roadmap](documentation/Roadmap.md)
