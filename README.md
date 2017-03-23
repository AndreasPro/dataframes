# DataFrame implementation for Rust

## TODO

- [ ] Define row and column objects
- [ ] 2-D access to items df[row, col]
- [ ] Numeric Column access df[1]
- [ ] Nominal column access df["c1"]
- [ ] Multi column access df[["c1", "c2"]]
- [ ] Row filtering on column selector df[1..3, ["c1", "c2"]]
- [ ] Boolean row filtering operations df[[true, false], ..]
- [ ] Column operations df["c1"] == 1 (probably won't be able to do this with in infix operator, but df["c1"].eq(1) would work
- [ ] Option to drop columns
- [ ] Option to add columns
