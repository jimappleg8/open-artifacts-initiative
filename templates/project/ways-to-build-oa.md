---
layout: sidebar-page
title: Ways to Build an Open Artifacts Project
eleventyNavigation:
  key: Ways to Build an Open Artifacts Project
  parent: project
  order: 5
tags: project
navKey: project-section
---
{% section %}

# Ways to Build an Open Artifacts Project

Open Artifacts projects have three main requirements:

1. They must be freely available, preferably online.
2. There must be a way for others to contribute to the project.
3. They must be open for reuse, remixing, and redistribution.

From a practical standpoint, that means you need to have:

1. A "home" for the project where people can find it
2. A place to store publicly available files about the project
3. A way for users and contributors to interact with your project
4. A license that makes clear what others can do with the project

To borrow some terminology from programming, you need a "stack" of tools and services to build your Open Artifacts project. Below are some common ways to build such a stack. They are not in any order of preference; the best choice depends on your specific needs and goals.

## Website only

**A Home:** A website works great to communicate your idea and give your project a home. You can use free services like GitHub Pages, Neocities, or WordPress.com to create a website for your project.

**Storage:** A website also provides a place to share files, instructions, and other resources related to your project. You can upload and link to source data, images, code snippets, and more.

**Interaction:** You can use comment sections, contact forms, or embedded social media feeds to allow users to interact with your project.

**License:** You can include a license file or section on your website to clarify how others can use your project.

## Website + Message Board

**A Home:** A website provides a central hub for your project, where you can explain its purpose and goals.

**Storage:** The website can host project files, resources, and documentation.

**Interaction:** A message board (like Discourse, Reddit, or a forum plugin) can facilitate user interaction, discussions, and contributions.

**License:** You can include license information on your website to clarify usage rights.

**Examples:** The [Hovalin 3D Printable Violin](https://www.hovalabs.com/work/hovalin) uses a website and a Discourse forum for interaction.

## Repository only

**A Home:** A code repository (like GitHub, GitLab, or Bitbucket) can serve as the central hub for your project. Many open-source software projects use the README file in their repository as their home page.

**Storage:** Repositories are designed to store files, making them ideal for hosting project resources, including code, data, and documentation.

**Interaction:** Repositories have built-in tools for collaboration, such as issue tracking, pull requests, and wikis, which facilitate user interaction and contributions.

**License:** You can easily add a license file to your repository to specify the terms of use for your project.

**Examples:** The [GliaX Stethoscope](https://github.com/GliaX/Stethoscope) project is hosted on GitHub.

## Repository + Website

**A Home:** A website provides a central hub for your project, where you can explain its purpose and goals. It gives you more flexibility in design and content presentation compared to a repository alone. The repository can be used to host the website as well as the project files.

**Storage:** The repository can store all the project files, while the website can link to these files and provide additional context and resources.

**Interaction:** The website can include comment sections, contact forms, or forums for user interaction, while the repository can handle contributions through issues and pull requests.

**License:** Both the website and repository can include license information to clarify usage rights.

**Examples:** This website itself is built using a repository (on GitHub) and a static site generator (Eleventy) to create the website.

## Social Media + Public Storage

**A Home:** Social media platforms (like Twitter, Instagram, or Facebook) can serve as a home for your project, allowing you to reach a broad audience and share updates.

**Storage:** Public storage services (like Google Drive, Dropbox, or Zenodo) can host your project files, making them easily accessible to users.

**Interaction:** Social media platforms provide built-in interaction features, such as comments, likes, and shares, facilitating engagement with your project.

**License:** You can include license information in your social media posts or link to a license file stored in your public storage.

**Examples:** The [HeaterBloc project](https://x.com/HeaterBloc) uses X and Google Drive.

## Wiki Website

**A Home:** A wiki platform (like Wikidot, Fandom, or MediaWiki) can serve as a collaborative home for your project, allowing multiple users to contribute and edit content.

**Storage:** Wikis can store various types of content, including text, images, and files, making them suitable for hosting project resources.

**Interaction:** Wikis have built-in collaboration tools, such as discussion pages and edit histories, facilitating user interaction and contributions.

**License:** You can include license information on your wiki pages to clarify usage rights.

**Examples:** The [Wikipedia](https://www.wikipedia.org/) platform is a well-known example of a collaborative wiki website. [Rep Rap](https://reprap.org/wiki/RepRap) is another example that uses a wiki to document 3D printing projects.


{% endsection %}