# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > typeapp-call > new`

```javascript
Program {
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 21
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: ' @flow'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 8
          index: 8
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
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
          column: 11
          index: 20
          line: 2
        }
        start: Object {
          column: 0
          index: 9
          line: 2
        }
      }
      expression: NewExpression {
        arguments: Array []
        leadingComments: undefined
        optional: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 19
            line: 2
          }
          start: Object {
            column: 0
            index: 9
            line: 2
          }
        }
        callee: ReferenceIdentifier {
          name: 'C'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 5
              index: 14
              line: 2
            }
            start: Object {
              column: 4
              index: 13
              line: 2
            }
          }
        }
        typeArguments: FlowTypeParameterInstantiation {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 8
              index: 17
              line: 2
            }
            start: Object {
              column: 5
              index: 14
              line: 2
            }
          }
          params: Array [
            FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: 'T'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 7
                    index: 16
                    line: 2
                  }
                  start: Object {
                    column: 6
                    index: 15
                    line: 2
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 16
                  line: 2
                }
                start: Object {
                  column: 6
                  index: 15
                  line: 2
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```
