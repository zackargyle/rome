# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > enum > members-strings`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 36
      line: 5
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TSEnumDeclaration {
      id: BindingIdentifier {
        name: 'E'
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 6
            index: 6
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
      }
      const: false
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 1
          index: 35
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      members: Array [
        TSEnumMember {
          id: StringLiteral {
            value: 'foo'
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 9
                index: 18
                line: 2
              }
              start: Object {
                column: 4
                index: 13
                line: 2
              }
            }
          }
          initializer: undefined
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 9
              index: 18
              line: 2
            }
            start: Object {
              column: 4
              index: 13
              line: 2
            }
          }
        }
        TSEnumMember {
          id: StringLiteral {
            value: 'bar'
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 9
                index: 29
                line: 3
              }
              start: Object {
                column: 4
                index: 24
                line: 3
              }
            }
          }
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 13
              index: 33
              line: 3
            }
            start: Object {
              column: 4
              index: 24
              line: 3
            }
          }
          initializer: NumericLiteral {
            value: 1
            format: undefined
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 13
                index: 33
                line: 3
              }
              start: Object {
                column: 12
                index: 32
                line: 3
              }
            }
          }
        }
      ]
    }
  ]
}
```
