# new-project

## Setting up Development Branch

Follow these steps to create a development branch and work on new features without affecting the main branch:

### 1. Clone the repository

```sh
git clone https://github.com/s94moiseiev/new-project.git
```

### 2. Navigate to the repository directory

```sh
cd new-project
```

### 3. Create a new branch named "development"

```sh
git branch development
git checkout development
```

### 4. Make your changes

You are now on the development branch and can start working on new features. Make your changes, stage them, and commit them:

```sh
git add .
git commit -m "Your commit message here"
```

### 5. Merge changes into main branch

Once you're done with your changes, you can merge them into the main branch:

```sh
git checkout main
git merge development
```

6. Push changes to GitHub

```sh
git push origin main
```

That's it! You've successfully set up a development branch for your project.
