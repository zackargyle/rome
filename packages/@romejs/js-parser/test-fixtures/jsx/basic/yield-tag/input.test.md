# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > yield-tag`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 36
      line: 4
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'it'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 11
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 35
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      head: FunctionHead {
        async: false
        generator: true
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 13
            index: 13
            line: 1
          }
          start: Object {
            column: 11
            index: 11
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 35
            line: 3
          }
          start: Object {
            column: 13
            index: 13
            line: 1
          }
        }
        body: Array [
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 18
                index: 33
                line: 2
              }
              start: Object {
                column: 4
                index: 19
                line: 2
              }
            }
            expression: YieldExpression {
              delegate: false
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 32
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 19
                  line: 2
                }
              }
              argument: JSXElement {
                name: JSXIdentifier {
                  name: 'a'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 12
                      index: 27
                      line: 2
                    }
                    start: Object {
                      column: 11
                      index: 26
                      line: 2
                    }
                  }
                }
                attributes: Array []
                children: Array []
                selfClosing: false
                typeArguments: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 17
                    index: 32
                    line: 2
                  }
                  start: Object {
                    column: 10
                    index: 25
                    line: 2
                  }
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
