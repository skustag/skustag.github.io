## Deployment
1. Fork this reporsitory to your reporsitory
2. Rename your repository to `<your-github-username>.github.io`
3. In `_config.yml`, set `url` to `https://<your-github-username>.github.io` and leave `baseurl` empty
4. Set up automatic deployment of the webpage:  
   (1) Click on **Actions** tab and **Enable GitHub Actions**  
   (2) Make any other changes to the webpage, commit, and push. This will automatically trigger the **Deploy** action  
   (3) Wait for a few minutes and let the action complete. If completed successfully, in addition to the `master` branch, your repository should now have a newly built `gh-pages` branch  
   (4) Finally, in the **Settings** of the repository, in the **Pages** section, set the branch to `gh-pages` (**NOT** to `master`)
5. Make changes, commit, and push. The webpage will be automatically re-deployed each time you push new changes to the repository
6. After deployment, the webpage will become available at `<your-github-username>.github.io`

## Local Setup
Install [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/), then do the following:
```bash
$ git clone git@github.com:<your-username>/<your-repo-name>.git
$ cd <your-repo-name>
$ bundle install
$ bundle exec jekyll serve
```
