## How to Contribute  
**Installation Guide**

Before getting started let's install the project on your system!!

### 1. 🔨 Setup & Run

Visit our GitHub repository and click on the **Fork** option in the top right corner of your GitHub account.
This creates a copy of the repository.


### 2. Clone the repository
**git clone** command creates a copy/clone of the repository in you local system.

--> You can clone this repo by using the below command and navigate to the directory.

```bash
git clone https://github.com/<YOUR_USERNAME>/HelloWorld.git
cd HelloWorld
```

### 3. Setup Remote

```bash
git remote add upstream https://github.com/<YOUR_USERNAME>/HelloWorld.git
```

### 4. Sync your fork or your local repository with the origin repository

  ```bash
  git checkout main
  git fetch upstream
  git merge upstream/main
  ```

### 5. Create a PR
After you are done making all the requisite changes. Push your changes to the repository and create a good PR.
