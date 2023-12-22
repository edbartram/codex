# SQL Database Projects Extension by Microsoft

## Keyboard Shortcuts

Created database projects as

* file - a single file containing CREATEs of all objects in database
* flat - one file for object, but nothing differentiating schema or whether it is a table or SP (other than name IF spu prefix was used). Strangely, if a table name is used more than once, the second has a number appended, ex: two.my_table becomes my_table_1. No mention of schema in the name - that's not useful!
* object - Tables are in a folder called Tables, but has same naming problem as flat. Close, but not quite useful
* schema - A weird mix of schema and database folders with a bunch of files at root level
* object-schema - this is what everyone seems to recommends, still a weird mix of schema and database folders

Disappointed none of those match how SQL Studio presents databases. Looks like I will stick with the recommended object-schema

[&#8593; Back to Top](#)

---

[&#8592; Back to README.md](../README.md)
