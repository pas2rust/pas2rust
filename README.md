<img src="https://github.com/pas2rust/pas2rust/raw/main/banner.gif" width="100%">
<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">

```rs
  Info::new()
    .os("Arch Linux")
    .wm("Hyprland")
    .zsh(true)
    .kitty(true)
    .rs(true)
    .backend(
      Backend::new()
        .sql(true)
        .actix_web(true)
        .diesel(true)
        .serverless(true)
        .ssg(true)
        .ssr(true)
    )
    .frontend(
      Frontend::new()
        .leptos(true)
        .tailwind(true)
        .css(true)
        .html(true)
        .js(true)  
    )
    .deploy(
      Deploy::new()
        .docker(true)
        .terraform(true)
        .aws(true)
        .google(true)
        .azure(true)
    )
```

<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">
