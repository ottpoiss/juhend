<h1>1)</h1> <h2>Loo githubis uus repository. Repository on seotud kataloogiga arvutis. Seega loo ka uus kataloog. Parem klahv ja avaneb github pats aken.</h2>
Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio
$ git init
Initialized empty Git repository in G:/kool/CSS&HTML/git_portfolio/.git/

2) 
Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)
$ git add -A

3)
Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)
$ git remote add origin https://github.com/ottpoiss/ottpoiss.github.io.git

4)
Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)
$ git commit -m "first"
[master (root-commit) 3509de3] first
 2 files changed, 95 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

5)
Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)
$ git push origin master

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.12 KiB | 1.12 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/ottpoiss/ottpoiss.github.io/pull/new/master
remote:
To https://github.com/ottpoiss/ottpoiss.github.io.git
 * [new branch]      master -> master
