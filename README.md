
# Han-Manual
This is the API manual for [Han.css][han-css]. Hosted on <http://css.hanzi.co/>. The manual currently corresponds to Han.css v3.0.0.

Documents of the manual, located in `doc/`, are written in Markdown/[CommonMark][stmd] format.

[han-css]: https://github.com/ethantw/Han
[stmd]: http://commonmark.org

## How to use
### Requirements

- Node.js 0.10.x
    - Jade
- Ruby
    - Sass 3.4.5

### Module dependencies
```
npm install
```

### Run locally and Sass watch
```
make run
```
Open <http://localhost:7788/> or <http://localhost:7788/manual> to see if it runs properly. Or use the command `npm start` if Sass is not installed.

### Compile the modification
```
make
```

## License
All files and documents of the manual are licensed under [Creative Commons BY-3.0][cc-by]

[cc-by]: https://creativecommons.org/licenses/by/3.0/
