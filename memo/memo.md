# 開発メモ

- [参考ページ](https://zenn.dev/daifukuninja/articles/13a35a8bb3a4a1)
- <https://github.com/L-I-V/MQL-Tools>

## 作業内容

```bash
> npm install -g yo generator-code
> yo code

? What type of extension do you want to create? New Language Support
Enter the URL (http, https) or the file path of the tmLanguage grammar or press ENTER to start with a new grammar.
? URL or file to import, or none for new:
? What's the name of your extension? MQL5
? What's the identifier of your extension? mql5
? What's the description of your extension? MQL5 Language Support
Enter the id of the language. The id is an identifier and is single, lower-case name such as 'php', 'javascript'
? Language id: mql5
Enter the name of the language. The name will be shown in the VS Code editor mode selector.
? Language name: MQL5
Enter the file extensions of the language. Use commas to separate multiple entries (e.g. .ruby, .rb)
? File extensions: .mq5
Enter the root scope name of the grammar (e.g. source.ruby)
? Scope names: source.mql5
? Initialize a git repository? Yes
```
