# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0161`

```javascript
Program {
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 8
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentBlock {
      id: '0'
      value: ' \n'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 2
          index: 6
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unknown start to an statement expression'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 0
          index: 0
          line: 1
        }
        start: Object {
          column: 2
          index: 6
          line: 2
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 3
          index: 7
          line: 2
        }
        start: Object {
          column: 2
          index: 6
          line: 2
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        leadingComments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 3
            index: 7
            line: 2
          }
          start: Object {
            column: 2
            index: 6
            line: 2
          }
        }
      }
    }
  ]
}
```
