# /fusebot github-dispatch <user/repo> <workflow_id> <branch/tag name>

This command triggers a github action with workflow_trigger action.

1. Type `/fusebot edit github-dispatch`.
2. Click the _edit_ link.
3. Copy and paste the [command.js](command.js) file content into the command.js file in the web editor.
4. Add `"octokit": "1.0.5"` into package.json as a dependency.
5. Set a personal access token in configuration with the key name of PAT.
6. Save.
7. Call `/fusebot github-dispatch` from Slack/Discord.
8. Modify and tinker!

## Note:

The PAT for this function requires the permission of repo:* and action:write to function.