# SQL vs. NoSQL Databases: What's the Difference?

1. SQL Databases:
Relational databases that use Structured Query Language (SQL) for defining and manipulating data.
Data is stored in tables with predefined schemas, enforcing strong consistency and ACID properties (Atomicity, Consistency, Isolation, Durability).
Examples include MySQL, PostgreSQL, SQLite.
Suitable for complex queries and transactions in structured data environments.

2. NoSQL Databases:
Non-relational databases that use various data models like key-value pairs, document stores, column-family stores, and graph databases.
Schema-less or flexible schema design allows for easy scalability and handling of semi-structured or unstructured data.
Examples include MongoDB, Cassandra, Redis.
Ideal for handling large volumes of data with dynamic schemas, distributed systems, and cloud environments.

# What is an ORM – The Meaning of Object Relational Mapping

1. Object Relational Mapping (ORM):
A programming technique that maps objects from object-oriented programming languages to relational database systems.
Provides a bridge between the database schema and application code, allowing developers to work with objects rather than SQL statements directly.
Automates common tasks such as CRUD operations (Create, Read, Update, Delete) and complex queries.
Examples include SQLAlchemy (Python), Hibernate (Java), Entity Framework (C#).

# Django Models

1. Django Models:
Part of the Django web framework for Python, providing an abstraction layer over relational databases.
Define data models using Python classes that inherit from django.db.models.Model.
Attributes in the model represent fields in the database table.
Supports relationships (ForeignKey, OneToOneField, ManyToManyField) and provides methods for interacting with the database.
Simplifies database access and management through an ORM, ensuring portability across different SQL databases like PostgreSQL, MySQL, and SQLite.