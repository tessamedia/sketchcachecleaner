# Sketch Cache Cleaner

![Sketch Cache Cleaner](https://image.ibb.co/mHOoea/cleaner.png)

# Sketch Cache Cleaner

Sketch Cache Cleaner is an app that deletes hidden Sketch history files that can take a lot of space on your hard drive and that you would probably never use.

---

1. [Warning](#warning)
2. [System Requirements](#system-requirements)
3. [Changelog](#changelog)
4. [Tips](#tips)
5. [Authors](#authors)
6. [License](#license)

---

### Warning

The app idea inspired by two blog posts: [How Sketch took over 200GB of our MacBooks](https://medium.com/@thomasdegry/how-sketch-took-over-200gb-of-our-macbooks-cb7dd10c8163) & [How to recover 50 GB or even more by deleting Sketch caches files](https://medium.com/sketch-app-sources/how-to-recover-50-go-or-even-more-by-deleting-sketch-caches-files-e5829dba20e1)

Please, read them in case you want to know how it works.

If your **workflow** relies on **automatic versioning** by macOS
(Time Machine etc.) - **DO NOT USE THIS APP!**

The app will remove all files in folder: `/.DocumentRevisions-V100/`

---

### System Requirements

- macOS 10.11+
- Xcode 10.0+
- Swift 4.2+

---

### CHANGELOG

**v 1.0.4**

- Build with Xcode 10 and macOS Mojave
- Migrate to Swift 4.2

**v 1.0.3**

- Add social sharing

- Code refactor

- Build with new Xcode's build system

**v 1.0.2**

Ported to Swift 4

**v 1.0.1**

- fix compatibility issues with 10.11, 10.12beta

**v 1.0.0**

- Initial release

---

### Authors

Idea & design: [Yuriy Oparenko](http://oparenko.com/)

Development: [Sasha Prokhorenko](https://twitter.com/minikin)

---

### Tips

- Use this app wisely.
- Reboot your Mac after app use.

---

### License

Sketch Cache Cleaner is distributed under the [MIT license](https://github.com/yo-op/sketchcachecleaner/blob/master/LICENSE.md).
