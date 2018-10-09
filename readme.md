<h1>1)</h1> <h2>Loo githubis uus repository. Repository on seotud kataloogiga arvutis. Seega loo ka uus kataloog. Parem klahv ja avaneb github bash aken.</h2>
<h3>Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio</h3>
$ git init
<h3>Initialized empty Git repository in G:/kool/CSS&HTML/git_portfolio/.git/</h3>

<h1>2)</h1> <h2>Kogub kokku failid, mis on kataloogis (local)</h2>
<h3>Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)</h3>
$ git add -A
<h3>NB! korduval failide lugemisl</h3>
$ git add .

<h1>3)</h1> <h2> Loob ühenduse githubi uue kataloogiga</h2>
<h3>Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)</h3>
$ git remote add origin https://github.com/ottpoiss/ottpoiss.github.io.git

<h1>4)</h1> <h2> Nimetab githubis uuenduse versiooni</h2>
<h3>Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)</h3>
$ git commit -m "first"
<h3>[master (root-commit) 3509de3] first
 2 files changed, 95 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css</h3>

<h1>5)</h1> <h2> Lükkab failid üles</h2>
<h3>Ott@Lenovo-PC MINGW64 /g/kool/CSS&HTML/git_portfolio (master)</h3>
$ git push origin master

<h3>Enumerating objects: 4, done.
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
 * [new branch]      master -> master></h3>

 