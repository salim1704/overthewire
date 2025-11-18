# Username
bandit6

# Password
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

# Solution
find files that meet criteria and discard all error messages.

```
find -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```

-type f tells the system to look for file types
-user tells system which user owns the file
-group what group the file belongs to 
-size is the size of the file and c denotes bytes


