gyazit
======

An instant screen capture app, inspired by Gyazo, with the power of Git!

Setup
-----

```
# Create a repository at GitHub or BitBucket, then...
git clone $clone_url /path/to/repo
cd /path/to/repo
git commit --allow-empty -m 'Initial commit'

cat <<END > ~/.gyazitrc
repository: /path/to/repo
branch: master
remote: origin
END
```

Usage
-----

Launch Gyazit and grab the screen. Gyazit commits the captured image,
pushes the repo to the remote, and copies the URL referring
the uploaded image to the pasteboard.
