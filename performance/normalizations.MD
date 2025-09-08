* Reduces data redudancy by organizing data into tables.
* Minimizes storage costs and eliminates anomalies.
* Can lead to complex joins and slower read pemance.

Denormalization:

- Introduce redudancy to reduce join ops and speed up read.
- Faster read p4mance.

When to use each:

1. Normalization: For transactional systems.
2. Denormalization: FOr reporting systems or  read heavy workloads.



Connection pooling:

- Technique used to manage database connections efficient by reusing established connection instead of creating new ones.

When to use it:

* Reduce overhead caused by frequent connection creation and teardown.
* Helps handle a large numbe rof concurrent connections effectively.



Materialized views.

- Precomputed query result stored as a table.
