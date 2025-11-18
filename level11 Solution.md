# Username
bandit11

# Password
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

# Solution
The data in data.txt has been rotated 13 places, this is known as rot13 and is a common encoding technique. To undo thiswe need to move all letters 13 places using tr.

```
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

This reads the data after moving it 13 places back to original text.
