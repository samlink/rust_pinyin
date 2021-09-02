# rust-pinyin
Change chinese sentence to pinyin initials

将汉字转成拼音首字母，用于自动完成的快捷拼音输入

## Installation

Add this to your Cargo.toml:

```
[dependencies]
rust-pinyin = "0.1"
```
## How to use:

```rust
use rust_pinyin::get_pinyin;

assert_eq!("zhq123vc", get_pinyin("张华强123vc"));
assert_eq!("bjyrysmyxgs", get_pinyin("北京益瑞盈商贸有限公司"));
assert_eq!("xnbjjsyxgs", get_pinyin("信念（北京）技术有限公司"));

```

