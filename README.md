cat main.rs
```rust
fn main() {
    greetings()
}

pub fn greetings() {
    println!("Hello 💊,  \n");
    langs();
}

pub fn langs() {
    println!(
        "
        Javascript \n
        Typescript \n
        Java \n
        Rust  \n
        Django \n
        Nestjs \n
        React \n
        Next \n
        Springboot \n
        Redux \n
        Node \n
        Nest \n
        express \n
        fastify \n
    "
    );
    ascci();
}

pub fn ascci ()  {
    println!(
        r"
        ___        _
        | _ \___ __| |_ _ ___
        |  _/ -_) _` | '_/ _ \
        |_| \___\__,_|_| \___/
        "
    )
}
```
