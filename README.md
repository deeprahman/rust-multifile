#### Command for  compiling  utils.rs
```
cargo build --package my_project --lib --target-dir build/utils
```

### Command for compiling main.rs
```
cargo build --package my_project --bin my_binary --target-dir build/main
```

Above command will create binary executable in 
```
build/main/debug/my_binary
```