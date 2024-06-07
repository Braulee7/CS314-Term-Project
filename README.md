# CS314 Group 21 Term Project _Minstant Messenger_


## Setup

Clone the project to your local machine recursively to get
both the front and back end directories

```bash
git clone --recursive https://github.com/Braulee7/CS314-Term-Project.git
```

Go into each of the directory sub modules to install the npm dependencies
by running `npm i` in each directory. From here you can run `npm run dev`
in the Front End directory to deploy the front end on your local-host.

To run the back end you need the .env file which contains all the sensitive
information like the Database credentials. These will be provided seperately.
After obtaining them you can run `npm run dev` in the backend directory
and have the server running on the localhost.

While you can run the server and client in the school systems, you cannot
connect to them from home since you need to be on the same network so I
recommend testing on your local machine, just make sure to have the
latest version of npm installed.

## Maintainment

Since the project here is in submodules, the front and back end are in there
own seperate git repositories. This is intentional for explicity modularity
between the two. When committing code you have to make sure you're in the
correct submodule directory before doing any git commands. Running `git status`
in the terminal is useful to identify this. Additionally the GitLens VS code
extension is helpful in identifying these submodules.

### Continuous Integration

I have set up Github Actions to run the automatic testing frameworks on the
independent directories. When you try to push your code to the main repo it
will be tested to make sure everything runs correctly with vitest on the front
end and supertest on the backend. I recommend doing test driven development,
that is write your tests first then start implementing your feature.

### Jira

Optional things you can do to keep maintainting our progress easier is by
syncing your progress with Jira. When committing code you can add the
story id to the front of the commit and Jira will automatically
sync that commit to the story enabling us to track what code is contributing
to each story.
**example**

```bash
git commit -m "CG21-20 added created query to send a message to the db"
```


# CS314 Group 21 Term Project _Minstant Messenger_

By: Braulio Reyes and Max Rego
(canvas id? idk)

### Structure and Implementation

That goes here!

### GitHub Link

link

### Implemented Tests

test

### Deployment Information

I think you can put info on how to deploy if we dont have a stable link

