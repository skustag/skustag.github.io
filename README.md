## Deployment
1. Rename the repository to `<your-github-username>.github.io`
2. In `_config.yml`, set `url` to `https://<your-github-username>.github.io` and leave `baseurl` empty
3. Set up automatic deployment of the webpage:  
   (1) Click on **Actions** tab and **Enable GitHub Actions**  
   (2) Make any other changes to the webpage, commit, and push. This will automatically trigger the **Deploy** action  
   (3) Wait for a few minutes and let the action complete. If completed successfully, in addition to the `master` branch, your repository should now have a newly built `gh-pages` branch  
   (4) Finally, in the **Settings** of the repository, in the **Pages** section, set the branch to `gh-pages` (**NOT** to `master`)
4. Make changes, commit, and push. The webpage will be automatically re-deployed each time you push new changes to the repository
5. After deployment, the webpage will become available at `<your-github-username>.github.io`
