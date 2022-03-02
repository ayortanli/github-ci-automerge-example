# github-ci-automerge-example
Auto merging main to another branch in Github CI

 
This is especially useful if you have a canary release deployed alongside the main release.  
In this example;  
Whenever the main branch has a commit, the main CI action will trigger the Canary CI action.  Then Canary CI action will auto-merge the main branch to itself and deploy accordingly.
