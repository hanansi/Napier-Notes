# Version Control and Git

### What is Version Control?
- Management of changes to documents or collections of information.
- Return to previous versions of our document if an error was made
- Branching - working and managing multiple versions of the document
- Merge - combine the information together into one of the branches

### Popular Version Control Tools
- Git
- Mercurial
- Subversion
- Visual SourceSafe and Visual Studio Team Services

### Version Control Approaches
- Localised - developers must be working on the same file-system
- Client-server - multiple developers can work locally and push changes to a single server repository
- Distributed - complete code-base and history is stored by each developer locally

### Some Terminology
| Term           | Definition                                                                                               |
| -------------- | -------------------------------------------------------------------------------------------------------- |
| Repository     | Is where the code and history is stored.                                                                 |
| Checkout/Clone | Process of getting a copy of the code from the repository. Client-server - checkout, Distributed - clone |
| Working copy   | Local version of the code-base.                                                                          |
| Fetch/Pull     | Get the most recent version of the code-base from the remote repository.                                 |
| Push           | Push our local changes to the remote repository. Must commit first.                                      |
| Commit         | New version of the code-base that contains the added changes in the local working copy.                  |
| Tag/Label      | Extra information we can add to a particular commit                                                      |
| Head           | special tag/label for the most recent commit on a branch                                                 |
| Branch         | Another version of the code-base. Are independent.                                                       |
| Master/Trunk   | Name of the main branch in a repository                                                                  |
| Merge          | Process of combining one branch into another                                                             |
| Conflict       | Occurs when different versions of the same document exists while merging branches which must be fixed    |
| Resolve        | Process of fixing conflicts                                                                              |

### What is Git?
- Distributed VCS where developers clone a complete copy of the repository, including its history, within local file system
- Created by Linus Torvalds
- It is fast, has data integrity features and is distributed
- Hidden folder `.git` contains history and other status information of the repository

#### Git commands

| Command    | Description                                                                    |
| ---------- | ------------------------------------------------------------------------------ |
| `init`     | Initialises a new Git repository                                               |
| `clone`    | Clones an existing Git Repository                                              |
| `add`      | Adds files to the staging area for a commit                                    |
| `status`   | Gets the current status of the Git repository                                  |
| `commit`   | Creates a new commit (checkpoint) in the code base                             |
| `push`     | Pushes the changes (commits) to a remote                                       |
| `diff`     | Provides information on differences between commits                            |
| `log`      | Provides history of Git commits                                                |
| `checkout` | Switches to a given branch or commit                                           |
| `fetch`    | Fetches changes from a remote repository                                       |
| `merge`    | Merges changes from another branch into the current one                        |
| `pull`     | Fetches and merges changes                                                     |
| `branch`   | Creates a new branch                                                           |
| `remote`   | Allows working with (e.g., adding, listing) remotes for the current repository |

#### Gitflow Workflow / Collaboration Model

| Branch    | Description                                                       |
| --------- | ----------------------------------------------------------------- |
| `master`  | The main branch                                                   |
| `develop` | The main development branch - work is normally undertaken here    |
| `feature` | The development of an actual feature, e.g., `feature/get-details` |
| `release` | Actual releases are tagged here                                   |
| `hotfix`  | Fixes to releases are undertaken here                             |

#git #github #versioncontrol 