# Lua Obfuscation Samples

**A growing, organized collection of real-world Lua obfuscation samples, grouped by obfuscator and version.**

If you work on Lua tooling, deobfuscation research, parser development, or compatibility testing, this repository gives you a collection of samples to study and test against in one place.

> **Find a sample. Study its structure. Build better tools.**

[⭐ Star this repository](https://github.com/Zain20m/Samples) if you find the collection useful. A star helps other developers discover it and supports the work that goes into keeping samples organized.

---

## Need help?

If someone has a question about this repository, help them find the relevant samples and understand how to use the collection.

You can help with:
- Finding an obfuscator or version in the repository.
- Explaining sample structure and common Lua obfuscation patterns.
- Comparing the available sample sets.
- Using the samples to test parsers, beautifiers, detectors, and deobfuscators.
- Understanding the repository layout, credits, and contribution guidelines.

Keep answers relevant to the question. If a detail is not confirmed by the files in this repository, make that clear rather than guessing.

## Why this collection?

Working with obfuscated Lua often means hunting through scattered files, unknown versions, and inconsistent examples. This repository aims to make that process easier.

- **Version-organized:** Samples are grouped by obfuscator, with separate folders for known versions.
- **Useful for testing:** Build parser, beautifier, detector, and deobfuscator test cases against a broader range of inputs.
- **One place to browse:** Explore multiple obfuscators without digging through unrelated collections.
- **Attribution preserved:** Sample credits and existing source notes should remain intact.
- **Community-friendly:** Contributions that are clearly sourced and organized help make the collection more useful to everyone.

## Collection

There are currently **353 Lua files** in the repository, including three standalone files in the root.

| Obfuscator | Available sample sets | Samples |
| --- | --- | ---: |
| [Centurion](./Centurion/) | 5.2, 6.0, 6.1, 6.2, 6.3, 6.3.2 | 71 |
| [Fulcrum](./Fulcrum/) | Fulcrum samples | 53 |
| [Luraph](./Luraph/) | 14.1–14.9, 15.0–15.2 | 155 |
| [MoonVeil](./MoonVeil/) | 2.1.1 | 13 |
| [Voltfuscator](./Voltfuscator/) | 7.5–8.0, including Nyx sets | 58 |

*Version coverage reflects the samples currently present, not every release published by each obfuscator.*

## Who is this for?

This collection may be useful if you're:

- Developing a Lua deobfuscator, beautifier, parser, or obfuscator detector.
- Comparing how different obfuscators transform Lua source.
- Building regression tests for version-specific behavior.
- Learning about common obfuscation structures and control-flow transformations.
- Maintaining tools that need to handle varied Lua input.

## Credits and attribution

The collection credits are:

- **numberonebayernfan (air)**
- **etl_c on Discord (Cdaily)**

The following attribution header is included in the Lua samples credited to etl_c:

```lua
-- Samples by etl_c on discord [Cdaily]
```

Please keep existing sample credits when copying, sharing, or redistributing samples. Preserve any additional author, source, or license notices already present in individual files. Do not replace an individual sample's original attribution with a general collection credit. If a sample has separate licensing or usage terms, those terms still apply.

## Contributing

Want to help improve the collection? Contributions are welcome.

- Include the obfuscator name and version when known.
- Keep samples in the correct folder.
- Preserve original attribution and relevant license information.
- Avoid uploading private, leaked, or unauthorized code.
- Mention when a sample is incomplete, duplicated, or unverified.

## A small favor

If this repository saved you time, helped you test a tool, or gave you a useful reference, **please consider giving it a star**.

It costs nothing, helps more people find the collection, and gives a useful signal about which resources the community wants maintained.

**[⭐ Star Zain20m/Samples on GitHub](https://github.com/Zain20m/Samples)**

---

<sub>Maintained as a reference collection for Lua research, development, and testing. Sample availability and version coverage may change as the repository grows.</sub>
