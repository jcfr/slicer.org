# slicer.org

This ``slicer-org`` branch of this repository store the static content served at the root of https://slicer.org.

# Synchronization

Every 5 minutes, the branch [slicer-org](https://github.com/Slicer/slicer.org/tree/slicer-org) is automatically
pulled into the live site. There is no need to connect to the server in order to make changes.

Source of the synchronization script: https://gist.github.com/freephile/13d8a570144f6449509d9679f6f28b8a#file-var-www-slicer-org-bin-pull-github-sh

# Local Development

1. [Fork][fork] this repository. We will assume your GitHub account is **yourname**.

2. Download the static content (Make sure to replace **yourname**):

```
git clone git@github.com:yourname/slicer.org
```

3. Update files in the directory `slicer.org` with you proposed changes.

4. Open `index.html` with your favorite browser. Go back to Step 3 until your are satisfied with the result.

5. Publish your branch and create a [pull request][pr]

[fork]: https://help.github.com/articles/fork-a-repo/
[pr]: https://help.github.com/articles/creating-a-pull-request/


# History

Transition to GitHub for managing and serving the Slicer top level page was discussed on Slicer Discourse forum. See https://discourse.slicer.org/t/its-all-about-transitions-lets-talk-about-slicers-landing-page


# License

It is covered by the Slicer License:

https://github.com/Slicer/slicer.org/blob/master/LICENSE
