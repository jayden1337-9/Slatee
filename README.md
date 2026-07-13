# Slate

# Slate

**Slate** is a free, open-source, cross-platform browser designed to support both the traditional web and the Slate ecosystem.

Browse normal websites with `https://` while also accessing native `slate://` pages built with the Slate language.

> ⚠️ Slate is currently in early development.

---

## Features (Planned)

- 🌐 Browse `https://`, `http://`, and other standard web protocols
- 🪨 Native `slate://` protocol support
- 📄 Render `.slate` files without additional software
- 💻 Built-in `slate://terminal`
- 📁 Local `.slate` file support
- ⭐ Bookmarks
- 📜 History
- 🔍 Built-in search
- 🌙 Dark mode
- 📱 Android
- 🍎 iOS
- 🪟 Windows
- 🍏 macOS
- 🐧 Linux

---

## What is Slate?

Slate is more than a browser.

It aims to provide a simple platform where anyone can create pages using the Slate language and browse them through the native `slate://` protocol.

A simple page can look like this:

```slate
Title: Hello, Slate!

Paragraph: Welcome to my first Slate page.

Button:
    Text: Learn More
    Link: slate://docs
```

No HTML or CSS required for basic pages.

---

## Project Structure

```
apps/
    browser/

packages/
    slate_parser/
    slate_renderer/
    slate_protocol/
    slate_widgets/

docs/
examples/
```

---

## Roadmap

### Phase 1
- [ ] Flutter browser
- [ ] Address bar
- [ ] HTTPS support
- [ ] Local `.slate` file support

### Phase 2
- [ ] `slate://` protocol
- [ ] Slate parser
- [ ] Slate renderer

### Phase 3
- [ ] `slate://home`
- [ ] `slate://settings`
- [ ] `slate://terminal`
- [ ] Downloads
- [ ] Bookmarks
- [ ] History

### Phase 4
- [ ] Public Slate network
- [ ] Search engine
- [ ] Developer tools
- [ ] Extensions

---

## Contributing

Contributions are welcome!

If you'd like to improve Slate, feel free to open an issue or submit a pull request.

---

## License

Licensed under the MIT License.
