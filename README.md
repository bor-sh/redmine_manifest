# Manifest

It handles multiple git repositories like redmine and plugins itself.

# Branching Draft

1. master - holds the current development 
2. develop_redmineversion - holds integration of one redmine release
3. release_redmineversion - holds release branch

# Install Repo

<pre>
curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo
</pre>

Put bin folder to PATH

# Repo init

<pre>
repo init -u git@github.com:mkinski/manifest.git
</pre>
