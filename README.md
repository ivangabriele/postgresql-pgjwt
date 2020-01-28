# PostgreSQL Docker image with pgjwt extension

[![img-travis]][link-travis]

A Docker image including:
- [PostgreSQL][link-postgres]
- [PostgreSQL pgjwt extension][link-pgjwt]

You can use it exactly as you would use the official [PostgreSQL Docker image][link-postgres].

The [PostgreSQL pgjwt extension][link-pgjwt] give you access to the following functions:

- `sign`
- `verify`

For more information about how to use these functions, please check their [readme][link-pgjwt-usage].

---

[img-travis]: https://img.shields.io/travis/com/ivangabriele/postgresql-pgjwt/master?style=flat-square

[link-pgjwt]: https://github.com/michelp/pgjwt
[link-pgjwt-usage]: https://github.com/michelp/pgjwt#usage
[link-postgres]: https://hub.docker.com/_/postgres
[link-travis]: https://travis-ci.com/ivangabriele/postgresql-pgjwt
