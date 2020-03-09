# heroku-buildpack-compact-slug
A simple Heroku Buildpack to reduce slug size

For now it just removes `app/assets`, which can't be added to `.slugignore` if they are needed for precompiling.
