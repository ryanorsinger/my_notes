# Codeup, May 30, 2015
## Agenda
- Attendance Easter Egg!
- Focused keyboard time on Ajax exercises
- Pair Programming and collaboration
- Code reviews
    
## Easter Egg

### Step 1: Configure a new site.dev on your Vagrant box
- From the `~/vagrant-lamp/` directory on your Mac 
    - Run `sudo ansible-playbook ansible/create-vagrant-site.yml -e "append_host=true"`
    - When prompted, input your Mac user password.
    - Name the site `your-github-username.dev`
    - Copy .html files you want to host into `~/vagrant-lamp/sites/your-github-username.github.dev/public`
    - Create folders for assets like `css`, `js`, `img`. Populate them as necessary.
    
### Step 2: Setup your GitHub Pages repo
- Login to your GitHub account and create a new repository named `username.github.io`
- The repo must be named exactly as your GitHub username followed 
- Follow the directions for 
    - Do `git init` from `~/vagrant-lamp/sites/github-username.dev/public` folder on your Mac.
    - `git add <filename>` or `git add -A` in order to add your desired files.
    - `git commit -m "first commit"`
    - `git push -u origin master`