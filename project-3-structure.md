### First use Ironlauncher to start the project and create the backend - we will use the json flag to create a json api template.

### In this example our project will be called 'projector'

```bash
$ npx ironlauncher projector --json
```

### Now we will go into this folder and create a react app there - this will be in a folder called 'client'

```bash
$ cd projector
$ npx create-react-app client
```

### Then we also want to remove git from within the client folder - otherwise you will get an error later if you use git in your project

```bash
# in: projector/client
$ rm -rf .git
```

### Then we want to add git to the root folder of our project

```bash
$ git init
```

### And then make the first commit

```bash
$ git add .
$ git commit -m 'initial commit'
```

### Then you go to GitHub, create a new repository for your project, copy the line 'git remote add origin ...' and push to master

Now we have our basic project structure 

Happy hacking 💙