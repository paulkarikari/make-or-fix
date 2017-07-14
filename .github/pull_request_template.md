#### Pre-Submission Checklist
<!-- Go over all points below, and after creating the PR, tick all the checkboxes that apply. -->
<!-- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->

- [x] Your pull request targets the `master` branch of the project.
- [x] Branch name is descriptive and in snake case format. Example `new_signup_feature`
- [x] All new and existing tests pass the command `phpunit --verbose --debug --colors`. 
  Use `git commit --amend` to amend any fixes.
- [x] Test coverage for the project is at a minimum 75%

#### Checklist:
<!-- Go over all points below, and after creating the PR, tick the checkboxes that apply. -->
<!-- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [x] Tested changes locally.

#### What does this pr do?
Describe in detail the functionality, feature, enhancement or bug this PR fixes. Where it helps, 
break this down into bullet points

#### How should this be manually tested?
Add specific steps on how to test this manually listed as bullet points
Example to test login feature: 
1. Start webserver
2. Open app url (`/login`) in the browser
3. Enter valid credentials (username: kofi, password: great) - this should redirect the user to say dashboard page
4. Logout current user
5. Repeat 1 through 2
6. Enter invalid credentials (kofi/notgreat) - this should display login failed response

##### Any background context you want to provide?
Any additional information the reviewer needs to be aware of

#### What are the relevant issues?
Links to the issue(s) addressed by this PR. Example #1 - for issue number 1

#### Screenshots (if appropriate)
UI and other screenshots

