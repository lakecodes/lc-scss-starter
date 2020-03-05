# lc-scss-starter
LC SCSS Starter Pack - *Just a good jumping off point.*


## Verion 0.5.5beta 
Built by [Lake County Board of County Commissioner's Office of Communications](https://lakecountyfl.gov/offices/communications/)


## Outside Vendors:
- <a href="https://getbootstrap.com/" target="_blank">Bootstrap (*v4.4.1*)</a>
- <a href="https://fonts.google.com/" target="_blank" title="Free fonts from Google">Google Fonts</a>
  - <a href="https://fonts.google.com/specimen/Barlow+Condensed" target="_blank" title="Barlow Condensed">Barlow Condensed</a>
  - <a href="https://material.io/resources/icons/?style=round" target="_blank" title="Material Icons (*Rounded*)">Material Icons (*Rounded*)</a>
  - <a href="https://fonts.google.com/specimen/Roboto" target="_blank" title="Roboto">Roboto</a>
  - <a href="https://fonts.google.com/specimen/Roboto+Condensed" target="_blank" title="Roboto Condensed">Roboto Condensed</a>


## Adding an existing project to GitHub using the command line
1. Initialize the local directory as a Git repository.
```
git init
```
2. Add the files in your new local repository. This stages them for the first commit.
```
git add .
# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
```
3. Commit the files that you've staged in your local repository.
```
git commit -m "Commit details"
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
```
4. In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
```
$ git remote add origin https://github.com/lakecodes/lc-scss-starter.git
# Sets the new remote
$ git remote -v
# Verifies the new remote URL
```
5. Push the changes in your local repository to GitHub.
```
$ git push origin master
# Pushes the changes in your local repository up to the remote repository you specified as the origin
```


## Changes
###### v0.5.7beta <2020-03-05>
- Removed CSS styles for YouTube links
- Revised README.md


###### v0.5.6beta <2020-03-05>
- Fixed broken variable
- Revised README.md


###### v0.5.5beta <2020-03-05>
- Added CSS styles for `.btn-go`
- Revised README.md


###### v0.5.4beta <2020-03-04>
- Included latest version of lc-ngui mixins into abstracts/_mixins.scss
- Corrected issue with Material Icons not loading
- Started adding dates to version changes in README.md
- Revised README.md


###### v0.5.3beta <2020-03-03>
- Removed *some* variables from individual stylesheets for testing purposes.  *Variable are still available to use, but are not used inside this start kit.*  I want to see if Angular compiles before using, or just uses.  I had some issues with the previous version not finding variable.  I am unsure if this is because they didn't exist, or a compiling issue.  This version should tell me which is the case.
- Added abstracts/_colors.scss
- Added abstracts/_fonts.scss
- Included latest version of lc-ngui buttons into components/_buttons.scss
- Revised README.md


###### v0.5.2beta <2020-02-28>
- Revised README.md


###### v0.5beta <2020-02-28>
- Added lc-ngui stylesheets for easy deployments into new projects.  *These files are intended for layout/structure.  Colors are kept to a minimum.*
  - lc-calendar-widget
  - lc-card
  - lc-content-callout
  - lc-esri-map
  - lc-footer
  - lc-header
  - lc-image
  - lc-link
  - lc-map 
  - lc-nav
  - lc-news
- Revised README.md


###### v0.4.1beta <2020-02-28>
- Revised README.md


###### v0.4beta <2020-02-28>
- Added Bootstrap 4.4.1 to __vendor-dir.scss
- Added Google Fonts __vendor-dir.scss
  - <a href="https://fonts.google.com/specimen/Barlow+Condensed" target="_blank" title="Barlow Condensed">Barlow Condensed</a>
  - <a href="https://material.io/resources/icons/?style=round" target="_blank" title="Material Icons (*Rounded*)">Material Icons (*Rounded*)</a>
  - <a href="https://fonts.google.com/specimen/Roboto" target="_blank" title="Roboto">Roboto</a>
  - <a href="https://fonts.google.com/specimen/Roboto+Condensed" target="_blank" title="Roboto Condensed">Roboto Condensed</a>
- Removed Font Awesome (*Sorry, folks*)
- Revised README.md