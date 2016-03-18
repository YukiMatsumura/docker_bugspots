# Bugspots

[Google Bugspots Tools.](http://google-engtools.blogspot.jp/2011/12/bug-prediction-at-google.html)  

```bash
Usage: bugspots /path/to/git/repo
    -b, --branch [name]              branch to crawl
    -d, --depth [depth]              depth of log crawl (integer)
    -w, --words ["w1,w2"]            bugfix indicator word list, ie: "fixes,closed"
    -r, --regex [regex]              bugfix indicator regex, ie: "fix(es|ed)?" or "/fixes #(\d+)/i"
        --display-timestamps         show timestamps of each identified fix commit
```

See [publickey](http://www.publickey1.jp/blog/12/bugspots.html) posts.  

## Package

 - Debian GNU/Linux 8
 - ruby 2.3.0
 - git 2.1.4
 - bugspots (latest)
