---
layout: page
title: Sync Obsidian Vault with GitHub Using MarkGit
include_in_header: true
---
# Sync Obsidian Vault with GitHub Using MarkGit


## Add GitHub credential
If we have not done that yet, we need [[1677384954.100572 | Login into GitHub with MarkGit]] so that MarkGit can communicate with GitHub

## Open Obsidian Vault
With MarkGit, click menu -> "Select a local repo", and navigate to the  Obsidian Vault. 
MarkGit might prompt "Do you want to initialize the folder as a git repo?", in that case, just click "OK" to confirm.


￼￼￼![](/MarkGit/assets/images/1677396213.593087.png)

## Create a GitHub for Obsidian Vault
Open "https://github.com" with your favoriate web browser, and create a new repo.

￼￼￼![](/MarkGit/assets/images/1677396320.611451.png)

<div class='y'>
Note:
we need select "Private" for our Obsidian Vault unless we are sure we want everyone to see the contents.
</div>


## Add Remote
With MarkGit, click the "i" icon at the top right, then click "Add remote"

Input the URL of the repo, then select GitHub credential.

￼￼￼![](/MarkGit/assets/images/1677396115.396241.png)

::: y 
Note: 
- If  "OAuth credential" is used, we need use the URL with the prefix of "https";
- If SSH key credential is used, we need use the "ssh" URL, which is in the format of "git@{host}:{path}"
:::


## Sync
With MarkGit, go to the "Sync" view (by clicking the 2nd icon at the bottom)

Then click the "Sync" button.

￼￼￼![](/MarkGit/assets/images/1677396140.549678.png)

Once it is completed, we will be able to browse our contents in GitHub!

￼￼￼![](/MarkGit/assets/images/1677396036.965742.png)

## Use ShortCuts to make sync easier
 Open the iOS built-in "Shortcuts" app,
- navigate to "Automation" tab, then click the "+" button at the top right
- Create a personal automation
- Find "App" 
- then click the app, find "Obsidian"
- Click "Next", then select "Apps" tab, and find "MarkGit"
- Select "Sync the default repo with remote"
- Click "Done" to save the automation

￼￼￼![](/MarkGit/assets/images/1677395970.415463.PNG)

When every time, when we open Obsidian, MarkGit sync UI can be popup and sync data for us!

<style>
    .mark-y, .y {
    padding: 1em;
    background-color: #CEBC81;
}
</style>
  



