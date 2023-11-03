# NSCCS Workshop Book

## Description

This book is a collection of workshops and presentations. It is a living document and should be edited and updated as needed. The book is an effort to assist in the transition of student leadership positions by providing all the information one would need to continue, adjust, and/or add workshops and presentations hosted by the club.

Instead of a random assortment of PowerPoints and other documentation that is easily lost when a student moves on from North Seattle College everything may live here.

## Set Up

This uses the command line tool [_mdbook_](https://rust-lang.github.io/mdBook/index.html) which is written in Rust.

### Prerequisites

Install [_Rust toolchain_](https://www.rust-lang.org/tools/install)

### Install Mdbook

```shell
cargo install mdbook
```

## How To Use

Read [Creating a Book](https://rust-lang.github.io/mdBook/guide/creating.html#creating-a-book) and specifically read the [Summary.md](https://rust-lang.github.io/mdBook/guide/creating.html#summarymd) section that shows the nested layout. The following code block is an example.

```markdown
- [Workshop or presentation topic](./topic_directory/README.md)
    - [Sub topic](./topic_directory/sub_topic_chapter_title)
```

Look at existing Chapters for further examples.
Hosted at [https://nsccs.github.io/](https://nsccs.github.io/)

