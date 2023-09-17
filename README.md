Create PostgreSQL extension with 100% Rust

## Reference
- [rust extension for Postgres: **pgcentralfoundation/pgrx**][1]
- [PL/Rust][2]

## Goal
- Create a **Posgres extension statement** to turn a column with **strings** of date values into a **float** (in hours)
- E.g.: `"1w 2d 4h 30m"` means 1 week, 2 days, 4 hours and 30 minutes. The function must turn it into **220.5 (hours)** 

[1]: https://github.com/pgcentralfoundation/pgrx
[2]: https://github.com/tcdi/plrust