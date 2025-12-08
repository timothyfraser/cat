# CAT Platform User Documentation

This directory contains user documentation for the CAT Platform, hosted as a [GitHub Pages site](https://timothyfraser.github.io/cat/).

## Working with This Submodule

This directory is a git submodule pointing to the public repository: https://github.com/timothyfraser/cat

### Making Changes

1. **Navigate to the userdocs directory:**
   ```bash
   cd analyzer/userdocs
   ```

2. **Make your changes** to the markdown files

3. **Commit and push to the public repo:**
   ```bash
   git add .
   git commit -m "Update documentation: [description]"
   git push origin main
   ```

4. **Update the submodule reference in the main repo:**
   ```bash
   cd ../..  # Back to dashboard root
   git add analyzer/userdocs
   git commit -m "Update userdocs submodule"
   git push origin <your-branch>
   ```

### Cloning the Main Repo

When someone clones the main dashboard repo, they need to initialize submodules:

```bash
git clone https://github.coecis.cornell.edu/CAT/dashboard.git
cd dashboard
git submodule update --init --recursive
```

### Updating the Submodule

To pull the latest changes from the public repo:

```bash
cd analyzer/userdocs
git pull origin main
cd ../..
git add analyzer/userdocs
git commit -m "Update userdocs submodule to latest"
```

## GitHub Pages Setup

The public repository (https://github.com/timothyfraser/cat) is configured for GitHub Pages:

1. Go to repository Settings → Pages
2. Source: Branch `main`, folder `/ (root)`
3. Site URL: https://timothyfraser.github.io/cat/

## Documentation Structure

See [table-of-contents.md](table-of-contents.md) for the complete documentation structure.




