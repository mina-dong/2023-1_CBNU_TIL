# 2023-1_TIL

최근에 좋은 기회로 github, gitbash 관련 강의를 듣게 되었다. TIL은 today i learned의 약어라고 한다. git commit과 git push를 이용해 꾸준히 작성해보고, Mark Down 문법에 익숙해고자 한다. 

* Computer Structure 컴퓨터구조
* Linear Algebra 선형대수학
* Object Oriented Design 객체지향설계

### Git bash error
+  ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'path'

hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
> git pull origin main  
> i, :wq  
> git push origin main


+ fatal: Unable to create '/home/runner/0000/.git/index.lock': File exists.

> rm -rf ./.git/index.lock