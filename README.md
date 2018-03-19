# Fun-Lua

Set of Functional Tools

1. Copy fun.lua to the project folder or in the directory in LUA_PATH

2. Import module as usual

local fc = require(fun)

3. See examples inside fun.lua

#Tool Box

gkv - print key, values and type of given table

lent - return number of all elements in give table

clone - return recursive copy of given table

copy - return first level copy of given table

range - return table with numbers

keys - return keys of given table

iskey, isval - return {k, v} if key/value in given table or false if not.

equal - return true if tables equal

join - return table that created from given two arguments

map - call a function to each element in the given table

mapr - call a function to each element in the given table recursevly

mapx - apply a function to each element in the given table

exem - call every function in table

filter - filter table by given function

partial - return function with fixed first argument

reduce - call a function to each element in the table to reduce the table to a single value

compose - return complex function constructed from two simple

randkey, randval - return random key/value from given table

shuffle - return the mixed version of given table

