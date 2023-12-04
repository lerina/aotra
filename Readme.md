If you use a personal access token to authenticate to github, and you should be using one, you may have encountered the below error when trying to push updates to a remote repository.

(refusing to allow a Personal Access Token to create or update workflow `.github/workflows/audit.yaml` without `workflow` scope)

Frustrating right! Well, fortunately this is easy to fix by following the steps below.

    Login to GitHub
    Go to Settings and choose Developer Settings
    Choose Personal Access Tokens
    Click the link on the personal access token used for your project
    Check the box beside workflow and click Update Token
