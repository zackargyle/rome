# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > 22`

```javascript
Program {
  corrupt: false
  directives: Array []
  filename: 'input.mjs'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.mjs'
    end: Object {
      column: 0
      index: 116
      line: 7
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
      value: '* @jsx mdx '
      loc: Object {
        filename: 'input.mjs'
        end: Object {
          column: 15
          index: 15
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
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: '<emphasis>import</emphasis> and <emphasis>export</emphasis> can only appear in a module'}
        advice: Array [
          log {
            category: 'info'
            text: 'Change the extension to <emphasis>.mjs</emphasis> to turn this file into a module'
          }
          log {
            category: 'info'
            text: 'Add <emphasis>"type": "module"</emphasis> to your <filelink emphasis target="package.json" />'
          }
        ]
      }
      location: Object {
        filename: 'input.mjs'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 35
          index: 51
          line: 2
        }
        start: Object {
          column: 0
          index: 16
          line: 2
        }
      }
    }
  ]
  body: Array [
    ImportDeclaration {
      defaultSpecifier: undefined
      importKind: undefined
      namespaceSpecifier: undefined
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.mjs'
        end: Object {
          column: 35
          index: 51
          line: 2
        }
        start: Object {
          column: 0
          index: 16
          line: 2
        }
      }
      source: StringLiteral {
        value: '@mdx-js/preact'
        loc: Object {
          filename: 'input.mjs'
          end: Object {
            column: 34
            index: 50
            line: 2
          }
          start: Object {
            column: 18
            index: 34
            line: 2
          }
        }
      }
      namedSpecifiers: Array [
        ImportSpecifier {
          leadingComments: undefined
          loc: Object {
            filename: 'input.mjs'
            end: Object {
              column: 11
              index: 27
              line: 2
            }
            start: Object {
              column: 8
              index: 24
              line: 2
            }
          }
          imported: Identifier {
            name: 'mdx'
            leadingComments: undefined
            loc: Object {
              filename: 'input.mjs'
              end: Object {
                column: 11
                index: 27
                line: 2
              }
              start: Object {
                column: 8
                index: 24
                line: 2
              }
            }
          }
          local: ImportSpecifierLocal {
            name: BindingIdentifier {
              name: 'mdx'
              innerComments: undefined
              leadingComments: undefined
              trailingComments: undefined
              loc: Object {
                filename: 'input.mjs'
                end: Object {
                  column: 11
                  index: 27
                  line: 2
                }
                start: Object {
                  column: 8
                  index: 24
                  line: 2
                }
              }
            }
            importKind: undefined
            leadingComments: undefined
            loc: Object {
              filename: 'input.mjs'
              end: Object {
                column: 11
                index: 27
                line: 2
              }
              start: Object {
                column: 8
                index: 24
                line: 2
              }
            }
          }
        }
      ]
    }
    ExportDefaultDeclaration {
      loc: Object {
        filename: 'input.mjs'
        end: Object {
          column: 1
          index: 115
          line: 6
        }
        start: Object {
          column: 0
          index: 53
          line: 4
        }
      }
      declaration: FunctionDeclaration {
        id: BindingIdentifier {
          name: 'MDXContent'
          loc: Object {
            filename: 'input.mjs'
            end: Object {
              column: 34
              index: 87
              line: 4
            }
            start: Object {
              column: 24
              index: 77
              line: 4
            }
          }
        }
        loc: Object {
          filename: 'input.mjs'
          end: Object {
            column: 1
            index: 115
            line: 6
          }
          start: Object {
            column: 15
            index: 68
            line: 4
          }
        }
        head: FunctionHead {
          async: false
          generator: false
          hasHoistedVars: false
          params: Array []
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.mjs'
            end: Object {
              column: 37
              index: 90
              line: 4
            }
            start: Object {
              column: 34
              index: 87
              line: 4
            }
          }
        }
        body: BlockStatement {
          directives: Array []
          loc: Object {
            filename: 'input.mjs'
            end: Object {
              column: 1
              index: 115
              line: 6
            }
            start: Object {
              column: 37
              index: 90
              line: 4
            }
          }
          body: Array [
            ReturnStatement {
              loc: Object {
                filename: 'input.mjs'
                end: Object {
                  column: 21
                  index: 113
                  line: 5
                }
                start: Object {
                  column: 2
                  index: 94
                  line: 5
                }
              }
              argument: JSXElement {
                name: JSXIdentifier {
                  name: 'h1'
                  loc: Object {
                    filename: 'input.mjs'
                    end: Object {
                      column: 12
                      index: 104
                      line: 5
                    }
                    start: Object {
                      column: 10
                      index: 102
                      line: 5
                    }
                  }
                }
                attributes: Array []
                selfClosing: false
                typeArguments: undefined
                loc: Object {
                  filename: 'input.mjs'
                  end: Object {
                    column: 20
                    index: 112
                    line: 5
                  }
                  start: Object {
                    column: 9
                    index: 101
                    line: 5
                  }
                }
                children: Array [
                  JSXText {
                    value: 'hi'
                    loc: Object {
                      filename: 'input.mjs'
                      end: Object {
                        column: 15
                        index: 107
                        line: 5
                      }
                      start: Object {
                        column: 13
                        index: 105
                        line: 5
                      }
                    }
                  }
                ]
              }
            }
          ]
        }
      }
    }
  ]
}
```
