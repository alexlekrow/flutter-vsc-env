# Flutter VSCode Environment

This repository contains a VSCode workspace adapted to the development of android applications using the Flutter framework.

It uses the _Remote: Containers_ extension from Microsoft for the Visual Studio Code editor. The extension allow you to develop inside the containers native file system using the VSCode installed on the host machine.

## Set-up

1) Install Docker, VS Code and the _Remote: Container_  extension.
2) Clone this repository.
3) Create a directory workspace inside the cloned repository folder,
4) Open Visual Studio Code and click on the green icon in the bottom left corner of the window.
5) From the popup menu choose: `Remote-Containers: Open Folder in Container..`
6) From the opened dialog navigate to the cloned repository, i.e. `flutter-vsc-env`,
7) Wait until the container building process is finished.

Run `flutter doctor` in a new terminal to check that everything is working okay.