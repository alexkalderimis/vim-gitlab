# vim-gitlab

vim-gitlab is a vim client for GitLab

* c.f. https://github.com/thinca/vim-github
* c.f. http://d.hatena.ne.jp/thinca/20100701/1277994373


GitLab ($B$N(B issues) $B$r(B vim $B$+$i;2>H!&JQ99$9$k%W%i%0%$%s$G$9(B.

- gitlab $B$O(B 6-1-stable $B0J2<$G$bF0:n$7$^$9$,(B issue #x $B$N?t;z$HI=<($5$l$k?tCM$,0lCW$7$^$;$s(B.
(API $B$,BP1~$7$F$$$J$$$?$a(B)



# Install

- required 
-- gitlab 6-2-stable
-- +python or curl or wget

# config


```vim
g:gitlab_config['__name__'] = {
\	'url' : 'http://localhost/',
\	'user' : '',
\	'email' : 'admin@local.host',
\	'password' : 'optional',
\}
```

```vim
:Gitlab __name__ issues root/sandbox
```
