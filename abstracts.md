# pg_classy: Classes in Postgres

Classes are a mainstay in all modern languages, and now they're available in Postgres as well. pg_classy allows you to define a "class" that contains any number of database objects: tables, functions, schemas, etc. Objects can be created dynamically, based on other objects in the database. For example, pg_classy comes with a class that creates constructor functions for composite types; you only need to provide the name of the type and pg_classy does the rest. This talk will demonstrate how to use classes as well as how to create new classes from scratch.

# All the dirt on VACUUM: 9.6 edition

The use of Multi-Version Concurrency Control (MVCC) is perhaps one of the most powerful features PostgreSQL has to offer, but it can be a source of confusion for new and experienced users alike. In this talk we will provide an in-depth walkthrough of why Postgres needs to vacuum and what vacuum does.

Topics:
- MVCC details
- HOT overview
- Identifying tuples to be vacuumed/frozen
- Visibility and Freeze map
- VACUUM and indexes
- Vacuuming heap pages


# How to safely use WITH in Postgres

Common Table Expressions (CTEs) can be very powerful, but are generally misunderstood and frequently abused. This talk will explain how CTEs actually work, the best way to use them, and how to understand those confusing recursive CTEs.

# Python + Jupyter + Postgres

Jupyter notebooks are a powerful tool for interacting with code. They provide a combination of documentation and interaction that works well for demos, education, presentation, as well as data exploration. This talk will demonstrate two methods for interacting with Postgres via both python and Jupyter notebooks.

# Demo: BigSQL, pgDevOps, pgBadger and plProfiler

BigSQL is an ecosystem of open-source projects related to Postgres. It includes Postgres versions, extensions, and related applications.

pgDevOps is a web front-end to BigSQL that makes managing one or a number of Postgres servers much easier. In addition to providing a GUI for BigSQL, it provides performance and configuration availability, as well as an interface for other web-based Postgres utilities.

pgBadger is a logfile analyzer for Postgres. It provides many metrics for a Postgres instance, all in a single HTML file.

plProfiler provides performance profiles for plpgsql functions, making it easy to pin down performance problems is any environment that is making use of functions.
