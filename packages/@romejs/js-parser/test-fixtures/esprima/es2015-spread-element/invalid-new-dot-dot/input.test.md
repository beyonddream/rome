# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-spread-element > invalid-new-dot-dot`

```javascript
Program {
  comments: Array []
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
      index: 12
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unknown start to an new expression argument'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 6
          index: 6
          line: 1
        }
        start: Object {
          column: 6
          index: 6
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
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
      expression: NewExpression {
        optional: undefined
        typeArguments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 10
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        callee: ReferenceIdentifier {
          name: 'f'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 5
              index: 5
              line: 1
            }
            start: Object {
              column: 4
              index: 4
              line: 1
            }
          }
        }
        arguments: Array [
          MemberExpression {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 9
                index: 9
                line: 1
              }
              start: Object {
                column: 6
                index: 6
                line: 1
              }
            }
            object: ReferenceIdentifier {
              name: 'INVALID_PLACEHOLDER'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 7
                  line: 1
                }
                start: Object {
                  column: 6
                  index: 6
                  line: 1
                }
              }
            }
            property: StaticMemberProperty {
              value: Identifier {
                name: 'g'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 9
                    index: 9
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 9
                  index: 9
                  line: 1
                }
                start: Object {
                  column: 8
                  index: 8
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