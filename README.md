# shnippets
Salvaging my Lucky Ants Snippets.app database to move it elsewhere.  With Rust.

## Notes

* Using [xq](https://github.com/jeffbr13/xq):
```
$ cat full.xml | xq '//object[@type="SNIPPET"]/attribute[@name="name"]'
```