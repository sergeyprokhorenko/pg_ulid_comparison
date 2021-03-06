# pg_ulid_comparison
Comparison of [ULID](https://github.com/ulid/spec) generation functions for PostgreSQL

Author | Repository | Stars | Ops/sec | Language | [CSPRNG](https://en.wikipedia.org/wiki/Cryptographically_secure_pseudorandom_number_generator) | [Monotonicity](https://github.com/ulid/spec#monotonicity) | Text format | Binary format | [UUID format](https://postgrespro.ru/docs/postgresql/13/datatype-uuid?lang=en) | Integer format | Last commit
--- | :---: | :---: | ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
[Edoceo, Inc.](https://github.com/edoceo) | [edoceo/pg-ulid](https://github.com/edoceo/pg-ulid) | 8 | [98359](https://github.com/edoceo/pg-ulid/issues/3#issue-773136417) | C | ✓ | ✓ | ✓ | - | - | - | 2019-10-29
[Vahagn Mkrtchyan](https://github.com/iCyberon) | [iCyberon/pg_ulid](https://github.com/iCyberon/pg_ulid) | 26 | ? | Go | ✓ | WIP | ✓ | WIP | - | - | 2021-03-28
[Dmitriy Mukhitov](https://github.com/RPG-18) | [RPG-18/pg_ulid](https://github.com/RPG-18/pg_ulid) | 2 | ? | C++ | ✓ | ✓ | ✓ | - | ✓ | - | 2021-02-22
[Datachoice Solutions Limited](https://github.com/geckoboard) | [geckoboard/pgulid](https://github.com/geckoboard/pgulid) | 56 | ? | PL/pgSQL | ✓ | - | ✓ | - | - | - | 2019-02-20
[Alex Nguyen](https://github.com/dharmaturtle) | [dharmaturtle's ULID in UUID format](https://github.com/geckoboard/pgulid/issues/3) | - | ? | PL/pgSQL | ✓ | - | - | - | ✓ | - | 2020-10-04
[Matthew Schinckel](https://github.com/schinckel) | [schinckel/ulid-postgres](https://github.com/schinckel/ulid-postgres) | 25 | ? | PL/pgSQL | - | - | ✓ | - | - | - | 2016-12-07 (WIP)
