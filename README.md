# shnippets
Salvaging my Lucky Ants Snippets.app database to move it elsewhere.  With Rust.

## Notes

* Using [hq](https://github.com/rbwinslow/hq):
```
$ cat full.xml | xq '//object[@type="SNIPPET"]/attribute[@name="name"]'
```