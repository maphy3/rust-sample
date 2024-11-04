# rust-sample

## コマンド

```bash
# 新規プロジェクトを作成する
$ cargo new hello_cargo
    Creating binary (application) `hello_cargo` package
note: see more `Cargo.toml` keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html


# プロジェクトをビルド
$ cd hello_cargo
$ cargo build
   Compiling hello_cargo v0.1.0 (/rust-docker/hello_cargo)
    Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.61s


# バイナリを生成せずにプロジェクトをビルドして、エラーがないか確認
$ cargo check
    Checking hello_cargo v0.1.0 (/rust-docker/hello_cargo)
    Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.06s


# プログラムをビルドして、実行する
$ cargo run
    Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/hello_cargo`
Hello, world!

```
Cargo は、target/debug ディレクトリにビルドの成果物を格納する
