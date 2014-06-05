show-gitlog
=============

Usage
-----------
```
> show-gitlog [find_path] [since] [author]
```

Example
-----------
```
> show-gitlog . 7.days.ago
sandbox
Fri Jun 6 02:41:17 2014: (HEAD, master):first commit

funnel-core
Tue Jun 3 01:01:46 2014: (HEAD, origin/master, master):first commit

psychoframe
Tue Jun 3 01:12:24 2014::first commit
Tue Jun 3 01:28:59 2014::Include capistrano
Tue Jun 3 01:33:46 2014::Add funnel
Wed Jun 4 03:14:12 2014: (origin/master, master):Receive serf event for capistrano
Fri Jun 6 02:32:16 2014: (HEAD, test):Add test file

show-gitlog
Fri Jun 6 02:41:58 2014::first commit
Fri Jun 6 03:27:15 2014::Add the show-gitlog command
Fri Jun 6 03:28:58 2014: (HEAD, origin/master, master):Update README.md
```

Contributing
-----------
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
