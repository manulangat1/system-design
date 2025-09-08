Indexes:

- Data structures that improve query p4mnace by reducing the amount of data scanned.

Types of Indexes:

1. B-Tree index - Common for exact match and range queries.
2. Hash Indexes - Best for equality comparisons.
3. Full Text Indexes. Used for searching large, textual data.
4. Bitmap Indexes. Suitable for low cardinality columns e.g gender

When to use Indexes:

1. Read heavy Operations: Indexes speed up query performance.
2. Write heavy systems : Be cautios as indexes can slow down inserts and updates.
