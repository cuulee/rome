# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 298`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      column: 26
      index: 26
      line: 1
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Object pattern cannot contains methods'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 11
          index: 11
          line: 1
        }
        start: Object {
          column: 7
          index: 7
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
          column: 26
          index: 26
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ArrowFunctionExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 26
            index: 26
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        body: NumericLiteral {
          value: 42
          format: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 26
              index: 26
              line: 1
            }
            start: Object {
              column: 24
              index: 24
              line: 1
            }
          }
        }
        head: FunctionHead {
          async: false
          hasHoistedVars: false
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 24
              index: 24
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
          params: Array [
            BindingObjectPattern {
              rest: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 19
                  index: 19
                  line: 1
                }
                start: Object {
                  column: 1
                  index: 1
                  line: 1
                }
              }
              properties: Array [
                BindingObjectPatternProperty {
                  key: StaticPropertyKey {
                    value: Identifier {
                      name: 'X'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 17
                          index: 17
                          line: 1
                        }
                        start: Object {
                          column: 3
                          index: 3
                          line: 1
                        }
                      }
                    }
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                      start: Object {
                        column: 3
                        index: 3
                        line: 1
                      }
                    }
                  }
                  value: BindingIdentifier {
                    name: 'X'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                      start: Object {
                        column: 3
                        index: 3
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                    start: Object {
                      column: 3
                      index: 3
                      line: 1
                    }
                  }
                }
              ]
            }
          ]
        }
      }
    }
  ]
}
```