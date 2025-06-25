#  Hello Async – Race Two URLs and Fetch the Fastest Title

A mini asynchronous Rust CLI tool that fetches two web pages concurrently and returns the page title of the one that responds first. ⚡️

This project showcases:
- Async programming with [`tokio`](https://docs.rs/tokio)
- HTML parsing with `trpl` and `Html::parse`
- Timeout handling for slow responses
- Graceful error management

---

### 🚀 Getting Started

Clone the repo:

```bash
git clone https://github.com/yourusername/hello-async.git
cd hello-async
```

Run the project with two URLs:

```bash
cargo run -- https://example.com https://httpbin.org/html
```

🙌 Contributions
Feel free to fork this repo and submit PRs. Ideas welcome!

