# Gno for Visual Studio Code

Welcome! 👋🏻<br/>
[The VS Code Gno extension]()
provides language support for the [Gnolang](https://github.com/gnolang/gno) and enhance your [Gnolang](https://github.com/gnolang/gno) development experience.

## Prerequisite

- Install [Go](https://golang.org) 1.18 or newer if you haven't already.

- Install [gofumpt](https://github.com/mvdan/gofumpt)

    ```
    go install mvdan.cc/gofumpt@latest
    ```

- Add Go bin to PATH

   e.g (For MacOS)

   - Open zsh shell configuration file
   ```
   nano ~/.zshrc
   ```
   - Add line given below
   ```
   export PATH="${PATH}:${GOPATH}/bin"
   ```

## Feature highlights

* [Syntax highlighting] - Syntax highlighting for Gno files
* [Formatting] - Automatically apply [gofumpt](https://github.com/mvdan/gofumpt) formatting on save
* [Precompile] - Precompile uses [gno](https://github.com/gnolhttps://github.com/gnolang/gno/tree/master/gnovm/cmd/gno). `gno` need to be installed for this feature to work. You can also enable precompile on save in the configuration. 
* [Snippets] - Templates that make it easier to enter repeating code patterns, such as loops or conditional-statements.
* [Diagnostics] -  Build, vet, and lint errors shown as you type or on save. Need `precompileOnSave` to be enabled.

## Contributing

We welcome your contributions and thank you for working to improve the Gnolang
development experience in VS Code.

## License

[MIT](LICENSE)
