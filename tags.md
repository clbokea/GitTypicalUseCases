# Tag
## Delete a tag from a remote Git repository.
If you have a tag named '12345' then you would just do this:    
````   
  git tag -d 12345
  git push origin :refs/tags/12345
  ````    

That will remove '12345' from the remote repository.

