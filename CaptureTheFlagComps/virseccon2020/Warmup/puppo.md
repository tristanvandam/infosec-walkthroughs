# 25 Points

```
Puppo
25

Awww, isn't this puppo so cute??? I can almost hear him barking... what does he say?

Download the file below.
```
run `strings woofer.jpg`
- I see lots of stuff. this interests me: `5b'TExTe2RvZ2dvX3NheXNfc3VjaF9iYXNlNjRfdmVyeV93b3d9'`.
- search of 5b encoding? MD5? => nothing...
- try base64 decoing the quoted text: `TExTe2RvZ2dvX3NheXNfc3VjaF9iYXNlNjRfdmVyeV93b3d9` and get the key

# FLAG
LLS{doggo_says_such_base64_very_wow}