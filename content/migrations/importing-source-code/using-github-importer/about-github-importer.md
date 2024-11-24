---
title: About GitHub Importer
intro: "If your source code is stored on another Git-based hosting service, you can move the code to {% data variables.product.prodname_dotcom_the_website %} using {% data variables.product.prodname_importer %}."
redirect_from:
  - /articles/about-github-importer
  - /github/importing-your-projects-to-github/about-github-importer
  - /github/importing-your-projects-to-github/importing-source-code-to-github/about-github-importer
  - /get-started/importing-your-projects-to-github/importing-source-code-to-github/about-github-importer
  - /articles/updating-commit-author-attribution-with-github-importer
  - /github/importing-your-projects-to-github/updating-commit-author-attribution-with-github-importer
  - /github/importing-your-projects-to-github/importing-source-code-to-github/updating-commit-author-attribution-with-github-importer
  - /get-started/importing-your-projects-to-github/importing-source-code-to-github/updating-commit-author-attribution-with-github-importer
  - /migrations/importing-source-code/using-github-importer/updating-commit-author-attribution-with-github-importer
versions:
  fpt: '*'
  ghec: '*'
---

## About {% data variables.product.prodname_importer %}

{% data variables.product.prodname_importer %} is a tool that quickly imports Git repositories from other hosting services to {% data variables.product.prodname_dotcom_the_website %}.

To get started with {% data variables.product.prodname_importer %}, see "[AUTOTITLE](/migrations/importing-source-code/using-github-importer/importing-a-repository-with-github-importer#importing-a-repository-with-github-

* {% data variables.product.prodname_importer %} imports the source code and commit history of a repository. It does not import other associated data from the hosting service, such as issues and pull requests.
* {% data variables.product.prodname_importer %} is only available on {% data variables.product.prodname_dotcom_the_website %}.
* During an import, you can authenticate with your remote repository. The repository must be accessible from the public internet. If the repository is hosted on a private network, {% data variables.product.prodnae_importer %} won't be able to access it.
* {% data variables.product.prodname_importer %} does not support repositories hat use version control systems other than Git, such as Mercurial, Subversion, or Team Foundation Version Control (TFVC). For more information abut alternatives to {% data variables.product.prodname_importer %}, see "[AUTOTITLE](/migrations/importing-source-code/using-the-command-line-to-import-source-code/about-source-code-imports-
* Repositories and individual files on {% data variables.product.pgithub)."
* {% data variables.product.prodname_importer %} does not move Git Large File Storage (LFS) objects from the source repository to the target repository. If you use Git LFS, you will need to either convert the Git LFS objects to regular files tracked b
