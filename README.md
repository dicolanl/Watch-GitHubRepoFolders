# Watch-GitHubRepoFolders
Azure Logic App to monitor specific GitHub repo folders for new commits

This logic app will run weekly and use the GitHub API to see if there are any new commits in the last week for a specific folder.  You can provide a list of repo folders in the format of "org/repo_folder/subfolder".  It will send an email if the folder has any new commits.

You will need a GitHub Personal Access Token which will be stored in key vault.