# Setting up a Gitbook -> GitHub integration
1. Create a new repo (preferably with a README - it's this one). We can use it to document about the content itself.
2. Create a master branch (main is now default) and make it default.
3. In the root, create a file .gitbook.yaml. Read here: https://docs.gitbook.com/integrations/github/content-configuration
4. Put `root: ./docs/` in it

Go to Gitbook.

A. Integrations -> GitHub
B. Choose the repository
C. Export and see files end up in GH.

Done.
