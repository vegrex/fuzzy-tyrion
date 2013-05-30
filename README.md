A
=======
Repo for OHTU exercises

Week 5 Exercise 4 - done
- many remote repositories
- pulled from added remote b (drunken-hipster)
- conflict solved

Week 5 Exercise 5 - done
- added remote repo git://github.com/mluukkai/ohtu2013.git as ohtu
- created tracking branch ohtu-lokaali
- added folder viikko2 from tracking branch to master and committed
- pushed master to origin and b (drunken-hipster)

Week 5 Exercise 6 - tags
- change one
- change two
- change three

Week 5 Exercise 6 - done
- added tag tagi1 before changes above
- added tag tagi2 after changes above
- added tag tagi1b for HEAD^ when on master
- added tag tagi1a for HEAD^^ when on master
- gitk displayed tags for the commits
- git status told "Not currently on any branch" when checking out tag

Week 5 Exercise 7 - done
- tested both new files and modifications with stash:
x staged new files are stashed
x unstaged new files are not stashed
x staged and unstaged modification are stashed
x staged modifications are only applied with --index

Week 5 Exercise 8 - done
- recovery of deleted file
- eight chars of the hexadecimal commit id string worked fine to check it out

Week 5 Exercise 9 - done
- reverted bad commit
- added branch haara
- committed changes on both master and haara (added yyy to haara)
- viewed branches with gitk --all
- made haara the new master by git reset --hard haara