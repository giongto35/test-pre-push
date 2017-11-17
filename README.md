# test-pre-push

This script is git client hook to reject all the commits related to prod folder to master branch. All the changes to other folder are still able to passed.
To make it works. Please run the following code to copy the hook to corresponding hook folder.

`cp pre-push-hooks .git/hooks/pre-push`



