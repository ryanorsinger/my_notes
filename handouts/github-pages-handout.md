# Codeup, May 30, 2015
## Agenda
- Attendance Easter Egg!
- Focused keyboard time on Ajax exercises
- Code Reviews

## Easter Egg

### Step 1: Configure a new site.dev on your Vagrant box
- From the `~/vagrant-lamp/` directory on your Mac
    - Run `sudo ansible-playbook ansible/create-vagrant-site.yml -e "append_host=true"`
    - Name the site `your-github-username.dev`
    - Copy .html files you want to host into `~/vagrant-lamp/sites/your-github-username.dev/public`
    - Create folders for assets like `css`, `js`, `img`. Populate them as necessary.

### Step 2: Setup your GitHub Pages repo
- Login to your GitHub account and create a new repository named `username.github.io`
- The repo must be named exactly as your GitHub username followed
- Follow the directions for adding a new project. They look like this:
    - Do `git init` from `~/vagrant-lamp/sites/<github-username.dev>/public` folder on your Mac.
    - Use your own username here: `git remote add origin git@github.com:<github-username>/<github-username>.github.io.git`
    - `git add <filename>` or `git add -A` in order to add your desired files.
    - `git commit -m "first commit"`
    - `git push -u origin master`
