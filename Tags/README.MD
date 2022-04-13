### TAG
git tag 

# TAG ADD 
git tag v1.0.0

# Annotated Tags
git tag -a v1.0.0 -m "my version 1.0.0"

# search tags 
git tag
git tag -l "v1.0.*"

# show tags
git show v1.4

# share tags - repository push
git push origin v1.0.1

# share tags multi update
git push origin --tags

# TAG Checkout
$ git checkout v1.0.1