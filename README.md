# MongoDB Lecture Notes

Today we will learn about a NoSQL database, MongoDB.

## Agenda

1. What is NoSQL
2. What is MongoDB
3. MongoDB Structure/Terminology
4. Mongo Shell
5. Querying with MongoDB

## Starting MongoDB

`mongod`

## Starting Mongo Shell

1. Open a new terminal window.
2. Type `mongo` and press Enter

### Helpful Shell Commands

**NOTE:** Wherever you see <thing>, replace <thing> with an actual word. Do not include the angle brackets.

* `help` - shows commands available in Mongo Shell
* `use <database>` - creates or switches to a database
* `db.<collection>.insert(<doc or array of docs)` - create a record or records
* `db.<collection>.find(<doc>)` - find documents that match doc
* `db.<collection>.update(...)` - update document(s)
* `db.<collection>.remove(<doc>)` - remove documents that match doc

## Terminology

* Collections
* Documents
* BSON

## MongoDB Documentation

[CRUD Operations]('https://docs.mongodb.com/manual/crud/')
