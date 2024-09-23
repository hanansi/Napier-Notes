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

