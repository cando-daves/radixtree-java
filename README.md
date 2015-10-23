Radix Tree Features of this Implementation

Utilizes loops instead of recursion for hopefully faster searches.

Almost all actions use a single common search function.

Tree is sorted in lexilogical (alphabetical) order.

Support for special handling for duplicate keys - good for keeping a count or list of values for a given key, etc.

Support for not continuing an insert after the search phase - good for tree reduction/simplification for example where all keys at a level have the same value.

Some core logic was derived from the project at http://code.google.com/p/radixtree/
