# Git-Flow

## Documentação - Get Started on Git Flow

-   Instalation on  ubuntu, you need install git-flow

```bash
    apt-get install git-flow
```

Your branch initial will be -> develop

To create a new feature on project, you need create a new point or new branch on project
for this see the command bellow

```bash
    git flow feature start (name_of_feature)
```

Now your branch will be switched to a -> for examples [ feature/css ]

Then you need create a new file for style the project 

Now you need add and commit on git 

```bash
    git add (name_of_file)
    git commit -m (your_message_commit)
```

Now to finished the feature, you need this command bellow

```bash
    git flow feature finish css
```