# learn_git_again
mkdir learn_git_again\
cd learn_git_again\
touch third.txt\
git init\
git add third.txt\
git commit -m "adding third.txt"\
git log\
touch fourth.txt\
git add fourth.txt\
git commit -m "adding fourth.txt"\
git log\
rm third.txt\
git add .\
git commit -m "removing third.txt"\
git log\
git config --global core.pager cat\
git config --global\
git config --global --list\
git remote add origin https://github.com/saftamed/learn_git_again-.git \
git push -u origin master
