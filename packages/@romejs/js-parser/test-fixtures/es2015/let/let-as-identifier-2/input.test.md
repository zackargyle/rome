# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > let > let-as-identifier-2`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 12
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 11
          index: 11
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 11
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'let'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 7
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 11
                index: 11
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: NumericLiteral {
              value: 1
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 11
                  index: 11
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
