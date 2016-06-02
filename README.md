# Publishing
'middleman-gh-pages' works by publishing the build files to the master branch of the github repo. This means that the source files will not be included in the repo. To get around this work on the 'dev' branch. When wanting to publish the site, merge dev into master and deploy using 'rake publish'.

Ensure the dev branch is pushed as to make a safe backup of the source files.