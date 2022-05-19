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

$ git tag -l 태그 목록 호출
$ git checkout v1.0.1
# Checkout & Branch Create
$ git checkout tags/<tag_name> -b <branch_name>
$ git checkout main (메인으로 돌아가기)
git checkout tags/<tag_name> -b <branch_name>

# 특정 버전 가져오는 방법.
$ git clone 깃저장소주소
$ cd 프로젝트명
$ git checkout 태그명
