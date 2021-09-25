# learning-react

Getting Started (first time developer on project):
- `git clone https://github.com/YOUR_GITHUB_USERNAME/belka.git` (go to the top where it says 'code' and copy the HTTPS link will work as well).
- `cd belka` - to go into the directory of Belka.
- `yarn` - to install the dependencies attached (yes, just `yarn` by itself).
- `yarn start` - to run local host development environment.
- Get to coding :)

General Workflow (any work being done on project):
- `git pull` - to pull any recent changes to the project made by other developers
- (do some coding working).
- `git add .` to  add to the staging process (yes, add the `.` at end).
- `git commit -m "Added a sexy feature that does x,y,z"` - to save that specific change. Generally good progress to save every bug fix or new feature in self commit.
- `git pull` - once again run to make sure most recent work is on your local machine.
- (OPTIONAL AND CAN SKIP) `git merge` - more complicated part if different code from local and remote. Rather complicated but follow tutorial here https://www.simplilearn.com/tutorials/git-tutorial/merge-conflicts-in-git
- `git push -u origin main` - to add your local changes to the remote repo.
- Rinse and repeat.

## Scripts to Utilize
*Must `cd` into the folder first before running any of these commands:*

* `yarn start` - runs the app in development mode. Please open [http://localhost:3000](http://localhost:3000) to view it in the browser (should automatically open on execution). Note that any changes in the code, upon save, will automatically update the [http://localhost:3000](http://localhost:3000) without any need to reload. To quit out of listener, close terminal or run `ctrl C` in terminal. **Most important and common command!**

* `yarn add somePackageNPM` - adds the specified 'somePackageNPM' package into the project. Please check out the [npm](https://www.npmjs.com/)  website for any packages to add and how to add them along with appropiate documentation. Note that you could also utilize `npm i somePackageNPM` but for consistency, please just use `yarn add` instead for this project.

* `yarn remove somePackageNPM` - removes the specified 'somePackageNPM' package.

* `yarn` - checks the `package.json` to see if there exists any packages that need to be installed. Running this command essentially just checks what packages are specified as being needed for this project that is not yet installed. In git repo's, usually the package names are listed but the packages are not actually on the repo to save space.

* `yarn build` - runs a product bundle of the React app. Really should only be used if ready to set onto live hosting.

## Tech Stack and Learning

For learning, I would recommend following this pattern. Learn a bit of JavaScript to at least build some simple functionality like working with vars, consts, and functions. Also highly recommended to learn a bit of git here After learning a bit of JS, I would then transition into React to see JS in practice and also learn React. Once you have a feel of JS and working comfortably with it, you can start reading more on the advanced topics in React such as useEffect, conditional rendering, and props. After that, I would say to start diving more deep into the packages of React Router, Redux, and then Firebase.

### General Timeline

So VERY generally:

- Days 1-4:
    - Beginner JavaScript
    - Beginner Git
- Days 4-6:
    - Intermediate JavaScript
    - Beginner React
- Days 6-8:
    - Intermediate React
    - Beginner Package Understanding (at least the concepts and why we use what we use)
- Days 8-10:
    - Advanced JavaScript
    - Advanced React
    - Beginner Firestore
- Days 10-14:
    - Firebase (other services like auth, storage, hosting, etc.)
    - Google Cloud Functions
    - Misc Google Cloud

Note this is just a roadmap, no need to follow exactly

### Tools and Resources
- Git
    - [Short Git Introduction](https://www.youtube.com/watch?v=USjZcfj8yxE)
    - [Additional Git Intro](https://www.youtube.com/watch?v=2ReR1YJrNOM)
    - [Git Vs. Github Explanation](https://www.youtube.com/watch?v=wpISo9TNjfU)
    - [Main Git Book](https://git-scm.com/book/en/v2)
    - [Nice Slides for Git (Stolen From My NYU Class)](https://nyu-computer-science.github.io/software-engineering/version-control-systems/#1) & [This Second Bulk of Slides](https://nyu-computer-science.github.io/software-engineering/git-and-github/#1)

- React & JavaScript
    - *Note for JavaScript, no need to learn about query selectors or interacting with the HTML, just know how to do functional stuff and work with arrays and objects.*
    - [Main JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
    - [Quick JavaScript Introduction](https://www.youtube.com/watch?v=c-I5S_zTwAc)
    - [Nice Video on Beginner Video Tutorial](https://www.youtube.com/watch?v=W6NZfCO5SIk)
    --------
    - [Main Facebook Documentation for React](https://reactjs.org/docs/getting-started.html)
    - [Documentation React Concept](https://reactjs.org/docs/hello-world.html)
    - [Quick React Introduction / Concepts Video](https://www.youtube.com/watch?v=MRIMT0xPXFI)
    - [More In-Depth React Tutorial (this is the video I watched when I first was learning React too :) ](https://www.youtube.com/watch?v=dGcsHMXbSOA)
    - [Long But Very Detailed React Tutorial Video](https://www.youtube.com/watch?v=Ke90Tje7VS0)
    ---------------
    - *These are more advanced topics in working with React Packages*
    - [React PACKAGE - Router Tutorial Video](https://www.youtube.com/watch?v=Law7wfdg_ls)
    - [React PACKAGE - Redux Tutorial Video](https://www.youtube.com/watch?v=CVpUuw9XSjY)
    - [React Package - Firebase](https://www.youtube.com/watch?v=mwNATxfUsgI)

- Firebase
    - [Main Firebase Documentation (can skip the setup and config process)](https://firebase.google.com/docs/web/setup)
    - [Specific Firestore Documentation of Interacting with Database](https://firebase.google.com/docs/firestore/manage-data/add-data)

- Google Cloud Functions
    - [Documentation for Google Cloud Functions](https://cloud.google.com/functions#section-4)
    - [Why Use Cloud Functions](https://firebase.google.com/docs/functions/use-cases)
---------------
- Additionals
    - [Final Deployment](https://drive.google.com/file/d/1uNGkOeYEOCRSieq2OgR4pdXYWYL7Z8Cu/view)
    - [YouTube Deployment Video Tutorial](https://www.youtube.com/watch?v=IDHfvpsYShs)
    - [How To Add Firebase Backups](https://levelup.gitconnected.com/how-to-back-up-firestore-easily-and-automatically-eab6bf0d7e1f) Note. you may need to find an updated version if needed.
    - [Installing Firebase Init](https://firebase.google.com/docs/hosting/quickstart)
---------------
