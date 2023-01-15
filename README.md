cat lib.rs
```rust
struct MoreAboutMe {
    technologies: Technologies,
}

impl MoreAboutMe {
    fn index() -> MoreAboutMe {
        MoreAboutMe {
            technologies: Technologies {
                frontend: Frontend {
                    javascript: vec!["React", "Next", "Redux"],
                    css: vec!["Materialize", "Tailwind", "Styled-components", "Bootstrap"],
                },
                backend: Backend {
                    java: vec!["Springboot"],
                    javascript: vec!["Node", "Nest", "Express", "Fastify"],
                    rust: vec!["Shuttle", "Rocket", "Actix"],
                    python: vec!["Django"],
                },
                db: vec!["MongoDB", "Postgres", "MySQL", "Sqlite"],
                dev_ops: vec!["Docker", "AWS", "Azure", "GCP"],
                misc: vec!["Firebase", "Socket.IO", "Postman", "Insomnia", "Xampp", "Eclipse", "Nginx", "Apache"],
            },
        }
    }
}

struct Technologies {
    frontend: Frontend,
    backend: Backend,
    db: Vec<&str>,
    dev_ops: Vec<&str>,
    misc: Vec<&str>,
}

struct Frontend {
    javascript: Vec<&str>,
    css: Vec<&str>,
}

struct Backend {
    java: Vec<&str>,
    javascript: Vec<&str>,
    rust: Vec<&str>,
    python: Vec<&str>,
}

```
