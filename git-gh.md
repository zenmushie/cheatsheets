gh pr create
Options
-a, --assignee <login>
Assign people by their login. Use "@me" to self-assign.
-B, --base <branch>
The branch into which you want your code merged
-b, --body <string>
Body for the pull request
-F, --body-file <file>
Read body text from file (use "-" to read from standard input)
-d, --draft
Mark pull request as a draft
-f, --fill
Use commit info for title and body
--fill-first
Use first commit info for title and body
-H, --head <branch>
The branch that contains commits for your pull request (default: current branch)
-l, --label <name>
Add labels by name
-m, --milestone <name>
Add the pull request to a milestone by name
--no-maintainer-edit
Disable maintainer's ability to modify pull request
-p, --project <name>
Add the pull request to projects by name
--recover <string>
Recover input from a failed run of create
-r, --reviewer <handle>
Request reviews from people or teams by their handle
-T, --template <file>
Template file to use as starting body text
-t, --title <string>
Title for the pull request
-w, --web
Open the web browser to create a pull request
Options inherited from parent commands
-R, --repo <[HOST/]OWNER/REPO>
Select another repository using the [HOST/]OWNER/REPO format
```
	gh pr create --title "{{title}}" --body "{{description}}"
	```
	