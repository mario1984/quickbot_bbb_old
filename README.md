# This repo has moved to GitHub and will be deleted in the near future.

New GitHub repo: https://github.com/o-botics/quickbot_bbb

In addition, there is a GitHub organization that contains many repos including this one. It is called o-botics: https://github.com/o-botics

And... there is a website O'Botics: http://o-botics.org


## Moving repos from Bitbucket to GitHub

*  Create a new repo on GitHub. Take note of the URL.
*  Rename remote and create new remote with GitHub URL.
	
		>> git remote rename origin bitbucket
		>> git remote add origin "https://URL"

*  Push each branch to new remote

		>> git push origin "branch"
		
*  If everything looks good remove Bitbucket remote

		>> git remote rm bitbucket