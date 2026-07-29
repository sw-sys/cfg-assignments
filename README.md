# cfg-assignments

`Hello world!`

#### This is Sheldon's CFGDegree Data Science assignment repo. From here you can go to:

- [Project examples](#project-examples)
- [Git commands](#git-commands)
- [.gitignore files](#gitignore-files)
- [requirements.txt explainer](#requirementstxt)
- [My favourite coding quote](#my-favourite-coding-quote)

---

## Project's I've completed so far

# Virtual Bookshelf

Designed, coded and prototyped a next.js app pulling data from supplier APIs to allow end users to browse catalogue records. This was supported by a mentor from Google and demonstrated the value of custom system solutions to our director.

    - [Demo video](https://mmutube.mmu.ac.uk/media/2025-02-05_Vir-Boo_Demo/1_lq9jvd5d)
    - [Repo](https://github.com/MMU-Library/virtual_bookshelf)

- Product managed an AI-enabled discovery layer using hybrid semantic search with cosign coefficient to allow an LLM access to records via a vectorised DB to rank and retrieve useful educational resources. This was supported by a Project Manager mentor and inspired my academic library industry to see we could make our own tools.

- Set up a github organisation account for my department and launched it with guidance documents and training. This has allowed our technical people to version, store and collaborate.
  - [Departmental Github](https://github.com/MMU-Library)

- Hosted a streamlit app to store worktools for myself and give easy access to colleagues who can't code or run projects locally. The tool enables users to quickly change the case of incorrect library records from upper to lower or standard MARC21 format. It also allowed customer service to generate QR codes or strip html tags for faster Drupal reviewing. The result is saved staff time and reduced frustration.
  - [Streamlit site](https://sheldonsworktools.streamlit.app/)
  - [Repo](https://github.com/sheldonmmu/work_tools)

- Established two community of practises, one for the department and one as part of a cross collaboration with other academic libraries. This enables us to discuss our projects, share our skills and knowledge. As a result, I was able to organise a meeting to get technical feedback and advice from a full time professional software team on worm projects to improve AI model choice and enhance features.

- Designed and ran an Introduction to Python session for nontechnical colleagues by teaching them about variables, basic functions like print() and input(). Most of them are English graduates so I started by getting them to build a story generator rather than doing operations to appeal to the audience. This gave them an insight in to some of the skills I use and increased their digital literacy. The session was highly rated in feedback and two participants went on to be self-taught and are still coding 3 years later.

# Git commands

**Useful git commands:**

- git status - check file changes and what's staged
- git ls-branch - list branches in the repo and their pointers
- git branch <branchname> - create a new branch
- git switch <branchname> - switch to the branch
- git branch -r - see all remote branches
- git branch -a - see all local and remote branches
- git branch -d <branchname> - delete the branch
- git checkout -b <newbranchname> - create branch and switch to it
- git push -u origin <branchname> - push to remote repo
- git add . - add all files to a branch
- git add <filenames> - add only specific file(s) to the stage
- git commit -m "initial commit" - add commits and messages
- git push - after assigning the commit message, push your changes to the remote repo once origin is set
- git fetch origin - pulls down any data that's changed in the repo while leaving your pointer untouched, even if the work has diverged
- git pull - to simply fetch the changes from the repo and upstream default branch

_There are also pull flags like no-rebase and squash - depending on how you want to merge your work in to the repo._

**When creating a new repo:**

- make a new repo on github
- mkdir and cd to the new folder locally with the same name - git init
- check which repo you're pointed to with git remote -v
- change using git remote add origin <remote_url_here>
- check the branch with git remote show
- Grab the remote files e,g, README with git pull origin <main>

Here are the [git docs](https://git-scm.com/docs)

# .gitignore files

These tell git to never stage and therefore prevent you from pushing to your repo. This both keeps your code more secure and reduces clutter in your repo.

API keys should never be put in here, use the credential manager. Speak to your supplier, if necessary, and always have a procedure with your team, ideally something written, so if anything leaks, the process is transparent and can be followed step by step and the security vunerability fixed by deactivating the key.

# requirements.txt

Record the packages (and version) needed for your repo here. This helps make transparent what the repo is building on, it hints at how big/complex the code base is, it helps with legacy code and making code run after time with the version details as often there are cross dependancy considerations - packages that used to work together at specific versions might need to be carefully considered if changed.

It also allows the user to quickly create a new environment and install what they need with `pip install -r requirements.txt` in the CLI.

# My favourite coding quote

> _"Perhaps what we need can be termed applied optimism: an attitude founded in expertise and an orientation towards problem solving, which looks clear eyed and undaunted at all the different potential modes of failure and thinks, ‘I’m sure we can figure out a way around that.’"_ - David Knott, [Look on the bright side](https://www.linkedin.com/pulse/look-bright-side-power-applied-optimism-david-knott-pyffe/?trackingId=jqZmuo8ESJKvq99ELy0Ecw%3D%3D)
