### Moonn

I love compilers and interpreters — the machinery that turns text a person writes
into something a machine will run. Mostly Go, Rust, and C.

I build **Mon**, a small statically-typed language with Mongolian keywords:

```mon
функц үндсэн() -> тоо {
    мөр_хэвлэх("Өдрийн мэнд\n");
    буц 0;
}
```

- [mon_lang](https://github.com/your-moon/mon_lang) — the compiler, in Go: source → Tacky IR → x86-64, assembled to a native binary.
- [mon](https://github.com/your-moon/mon) — the same language, now **self-hosted**: the compiler is written in Mon, emits Mach-O directly, and bootstraps from a seed with no external toolchain. There's a TinyGL-style software 3D renderer written in Mon.
- [Cecile](https://github.com/your-moon/Cecile) — an earlier bytecode language in Rust: GC'd, typed, with a REPL.
- [gpc](https://github.com/your-moon/gpc) — a static preload checker for GORM.
- [kaleidoscope](https://github.com/your-moon/kaleidoscope) — the LLVM front-end, in C++.

The books I keep coming back to:

- *Crafting Interpreters* — Robert Nystrom
- *Compilers: Principles, Techniques, and Tools* — Aho, Lam, Sethi & Ullman
- *Computer Systems: A Programmer's Perspective* — Bryant & O'Hallaron

> 独行道 — the way of walking alone.
