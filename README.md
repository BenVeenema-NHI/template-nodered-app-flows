template-nodered-app-flows
==========================

### About

This is a nearly blank, starting set of flows and settings for a Node-Red project. It is designed to be used with the template-nodered-app-environment[https://github.com/BenVeenema-NHI/template-nodered-app-environment]

### First Use
After creating a new environment using template-nodered-app-environment[https://github.com/BenVeenema-NHI/template-nodered-app-environment], you will launch Node-Red for the first time, clear the introduction and tell it you want to "Clone a Repository". That repository is this repository (after you've forked it and given it a nice new name). You'll enter a git username and email, this can be anything, but should be your github username and email address. You'll then come to a screen where you need to enter the repository uri. Use SSH! You'll paste in the SSH URL which will then change the form and ask for an SSH Key. Since you don't have one, you'll click on "Add Key" which will guide you through creating a new key. Use your name in the key so future people know who it belongs too! After creating the key, the guide for completing the git clone will be gone. So close Node-Red and open it again, then, once you get back to the SSH clone screen, you can use the key you generated.

We won't be using Credentials Encryption so leave that blank. All credentials will be provided at run-time by the environment and a config file there. THIS IS VERY IMPORTANT! DO NOT CHECK IN CREDENTIALS TO THE REPO!
