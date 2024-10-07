# soul of reason 🎙️

## getting started
1. clone the repo and change directory into it
    ```
    git clone https://github.com/nyu-dh/soul-of-reason.git
    cd soul-of-reason
    ```
2. install the ruby dependencies
    ```
    bundle install
    ```
3. serve the site locally
    ```
    bundle exec jekyll serve
    ```
    (use `ctrl-c` to quit)
4. check out a new branch to make changes
    ```
    git checkout -b my-branch-name
    ```
5. stage, commit, and push changes when you are ready
    ```
    git add .
    git commit -m "these are the changes i made"
    git push --set-upstream origin my-branch-name
    ```
6. to publish the changes on the live site, create and merge a [pull request](https://github.com/nyu-dh/soul-of-reason/pulls) between your new branch and `main`.
