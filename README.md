``` rust
fn main() {
    let mut details: Vec<(&str, &str)> = Vec::new();

    details.push(("name", "simon danielsson"));
    details.push(("age", "25"));
    details.push(("occupa.", "guitarist, producer, recreational programmer"));
    details.push(("contant", "contact@simondanielsson.se"));
    details.push(("website", "https://www.simondanielsson.se/"));

    for (f, d) in details {
        println!("{f:<8}: {d}")
    }
}
```
