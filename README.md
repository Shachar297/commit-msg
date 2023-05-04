# btb hooks

## Mail Goal

#### The main goal of this script [prepare-commit-msg.sh](./prepare-commit-msg.sh) is to automatically change the git commit message if the current branch is related to a jira ticket, if so, the jira ticket related commits will automatically increased.

---

## Installation && Integration

#### This script rely on few things that are mandatory.

1.  Git bash installed on each machine.

    - If you are not sure git bash is installed, you can do one of two things
      Open Visual Studio code -> Terminal -> <img src="./src/Terminal.png"> </img>
      - If you see bash option, you are good to go.
    - Open any folder on your windows. right click ->
      <img src="./src/win-save.png"> </img>
      - If you see 'git bash here', you are good to go.

2.  Do not remove or change location of this script.

    - The path of the script is where you have cloned this repository to.

3.  Set git config global parameter of the path of the script
    ```
    git config --global core.hooksPath repo-location
    ```


<img src="./src/cfg.png"> </img>