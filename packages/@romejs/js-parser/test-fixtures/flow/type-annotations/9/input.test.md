# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 9`

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
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 44
      index: 44
      line: 1
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
        name: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 12
            index: 12
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
          column: 44
          index: 44
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 44
            index: 44
            line: 1
          }
          start: Object {
            column: 42
            index: 42
            line: 1
          }
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 42
            index: 42
            line: 1
          }
          start: Object {
            column: 12
            index: 12
            line: 1
          }
        }
        params: Array [
          BindingIdentifier {
            name: 'callback'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 21
                index: 21
                line: 1
              }
              start: Object {
                column: 13
                index: 13
                line: 1
              }
            }
            meta: PatternMeta {
              optional: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 41
                  index: 41
                  line: 1
                }
                start: Object {
                  column: 13
                  index: 13
                  line: 1
                }
              }
              typeAnnotation: FlowFunctionTypeAnnotation {
                rest: undefined
                typeParameters: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 41
                    index: 41
                    line: 1
                  }
                  start: Object {
                    column: 23
                    index: 23
                    line: 1
                  }
                }
                returnType: NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 41
                      index: 41
                      line: 1
                    }
                    start: Object {
                      column: 35
                      index: 35
                      line: 1
                    }
                  }
                }
                params: Array [
                  FlowFunctionTypeParam {
                    name: Identifier {
                      name: '_'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 25
                          index: 25
                          line: 1
                        }
                        start: Object {
                          column: 24
                          index: 24
                          line: 1
                        }
                      }
                    }
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 30
                        index: 30
                        line: 1
                      }
                      start: Object {
                        column: 24
                        index: 24
                        line: 1
                      }
                    }
                    meta: PatternMeta {
                      optional: false
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 30
                          index: 30
                          line: 1
                        }
                        start: Object {
                          column: 24
                          index: 24
                          line: 1
                        }
                      }
                      typeAnnotation: BooleanKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 30
                            index: 30
                            line: 1
                          }
                          start: Object {
                            column: 26
                            index: 26
                            line: 1
                          }
                        }
                      }
                    }
                  }
                ]
              }
            }
          }
        ]
      }
    }
  ]
}
```
