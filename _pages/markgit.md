[[note-graph]]
## Issues
- [x] submodule credential not found after cloning
  - [x] fetch before checkout
  - [x] credential match for ssh
  - [x] discard submodule change
- [x] open file from diff view
- [x] credential not saved when cloning? 
- [ ] oauth token expiration
  https://github.com/OAuthSwift/OAuthSwift/wiki/OAuth-2.0-Token-Expiration
  need to store both `oauthRefreshToken` and `oauthTokenExpiresAt`
not do do, github does not provide refresh token
- [x] oauth logout
- [x] ui: progress color
- [x] ui: credential management, button not showing after login/logout
- [x] crash when working together on the same folder with InstantCoder
- [x] typing too fast will cause cursor move to the beginning and clear the text
- [x] editor: +someloss
- [x] ui: "close" button too big gap caused by big width
  - [x] branches

- [x] ui: iphone repo clone: not be able to click "clone" button 
- [x] ui: alert message on unstaged changes
- [x] ui: status not updated on pull and merge

- [x] github personal access token
- [x] failed to create diff
- [x] clone failed and crash
- [x] git status slow
  - [x] sometimes never stop
- [x] not be able to read name from oauth user api
  - [x] github
  - [x] gitlab
  - [x] gitee
- [x] iphone, not be able to input personal access token
- [x] git: status slow, never stop
  - [x] cancel previous update status operations

- [x] layout: branch status too close to pull/push buttons (light mode)
- [x] git: file tree not refreshed after git pull
## Reference
[[code-tools]]
nodejs
https://github.com/1Conan/nodejs-mobile/tree/upstream-node-v16.14.x-ios

## Features
- [ ] capture web page as markdown
  - [ ] temp storage  
  - [ ] basic function
  - [ ] download all resources 
- [ ] https://github.com/rhysd/vim.wasm but cannot work on ios
- [ ] more git operations: pull, push
- [x] shortcuts
  - [x] pull
  - [x] push 
- [ ] wiki: navi-back
- [ ] wiki: reminder on renaming a md file
- [ ] wiki: erminder on renaming an image file
- [ ] markdown icon
- [ ] editor: markdown enhancement
  - [x] highlight: wiki
  - [ ] hover
- [ ] wiki: tag
- [x] wiki: autocomplete
- [x] wiki: resource link autocomplete
- [ ] wiki: back link
- [x] ui: git querying status indicator and hide
- [x] ui: change to in progress status when buttons clicked
- [x] ui: import file
- [x] ui: show file/path name in diff view 
- [ ] ui: import photo
- [ ] git: reload current file if it is changed
- [x] git: auto generate commit message based on changed files
- [x] git: import SSH keys
- [x] git: submodule
  - [x] clone
  - [x] status
  - [x] commit
- [ ] git: compare current with a commit
- [ ] git: support non-git folder
- [x] git: remote add/remove 
- [x] git: init git repo
- [ ] git: import zip file as a repo
- [ ] git: compare 2 commits
- [x] git: add to ignore
- [ ] ui: editor options to set font/size

```
repo --- remote --- credential
```