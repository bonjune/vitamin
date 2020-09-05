# vitamin
Writing clean code in Bootstrap project

# Roadmap

1. HTML linter backed by HTML parser with FParsec
2. VSCode Extension Support
    - Language Server Protocol

# HTML lint

## It validates...

- Bootstrap classname (e.g. `contianer` -> `container`)
- layout (e.g. `container>col>row` -> `container>row>col`)
- component (e.g. `navbar-nav>navbar` -> `navbar>navbar-nav`)
- target id (e.g. checks if there exists `#id-selector`)
