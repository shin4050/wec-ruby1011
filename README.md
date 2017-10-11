# wec-ruby1011
## 実行ログ
shin4050:~/workspace $ mkdir wec-ruby1011
shin4050:~/workspace $ 
shin4050:~/workspace $ cd wec-ruby1011/
shin4050:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
shin4050:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
shin4050:~/workspace/wec-ruby1011 (master) $ git add README.md
shin4050:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) de7c906] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
shin4050:~/workspace/wec-ruby1011 (master) $ git remote add origin https://github.com/shin4050/wec-ruby1011.git
shin4050:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com': shin4050
Password for 'https://shin4050@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/shin4050/wec-ruby1011.git/'
shin4050:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com': shin4050
Password for 'https://shin4050@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 235 bytes | 235.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/shin4050/wec-ruby1011.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
shin4050:~/workspace/wec-ruby1011 (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
shin4050:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.1.gem (100%)
Successfully installed pry-0.11.1
3 gems installed
shin4050:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> quit
shin4050:~/workspace/wec-ruby1011 (master) $ sudo gem install bundler
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
1 gem installed
shin4050:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
shin4050:~/workspace/wec-ruby1011 (master) $ bundle install
Fetching gem metadata from https://rubygems.org/.............
Fetching version metadata from https://rubygems.org/.
Resolving dependencies...
Using bundler 1.15.4
Fetching mini_portile2 2.3.0
Installing mini_portile2 2.3.0
Fetching nokogiri 1.8.1
Installing nokogiri 1.8.1 with native extensions
Bundle complete! 1 Gemfile dependency, 3 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
shin4050:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rb
"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲームクリエイターに強い専門学校"
shin4050:~/workspace/wec-ruby1011 (master) $ 