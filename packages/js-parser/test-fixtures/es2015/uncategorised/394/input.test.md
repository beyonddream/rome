# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 394`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/uncategorised/394/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/394/input.js"
		end: Object {
			column: 0
			index: 44
			line: 5
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Invalid parenthesized binding"}]}
			}
			location: Object {
				filename: "es2015/uncategorised/394/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 2
					index: 9
					line: 2
				}
				start: Object {
					column: 1
					index: 8
					line: 2
				}
			}
		}
	]
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "es2015/uncategorised/394/input.js"
				end: Object {
					column: 6
					index: 6
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "es2015/uncategorised/394/input.js"
					end: Object {
						column: 6
						index: 6
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "a"
							loc: Object {
								filename: "es2015/uncategorised/394/input.js"
								identifierName: "a"
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
						init: undefined
						loc: Object {
							filename: "es2015/uncategorised/394/input.js"
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
				]
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/394/input.js"
				end: Object {
					column: 9
					index: 16
					line: 2
				}
				start: Object {
					column: 0
					index: 7
					line: 2
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/uncategorised/394/input.js"
					end: Object {
						column: 8
						index: 15
						line: 2
					}
					start: Object {
						column: 0
						index: 7
						line: 2
					}
				}
				right: JSObjectExpression {
					properties: Array []
					loc: Object {
						filename: "es2015/uncategorised/394/input.js"
						end: Object {
							column: 8
							index: 15
							line: 2
						}
						start: Object {
							column: 6
							index: 13
							line: 2
						}
					}
				}
				left: JSAssignmentIdentifier {
					name: "a"
					loc: Object {
						filename: "es2015/uncategorised/394/input.js"
						identifierName: "a"
						end: Object {
							column: 2
							index: 9
							line: 2
						}
						start: Object {
							column: 1
							index: 8
							line: 2
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/394/input.js"
				end: Object {
					column: 11
					index: 28
					line: 3
				}
				start: Object {
					column: 0
					index: 17
					line: 3
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/uncategorised/394/input.js"
					end: Object {
						column: 10
						index: 27
						line: 3
					}
					start: Object {
						column: 0
						index: 17
						line: 3
					}
				}
				right: JSObjectExpression {
					properties: Array []
					loc: Object {
						filename: "es2015/uncategorised/394/input.js"
						end: Object {
							column: 10
							index: 27
							line: 3
						}
						start: Object {
							column: 8
							index: 25
							line: 3
						}
					}
				}
				left: JSMemberExpression {
					loc: Object {
						filename: "es2015/uncategorised/394/input.js"
						end: Object {
							column: 4
							index: 21
							line: 3
						}
						start: Object {
							column: 1
							index: 18
							line: 3
						}
					}
					object: JSReferenceIdentifier {
						name: "a"
						loc: Object {
							filename: "es2015/uncategorised/394/input.js"
							identifierName: "a"
							end: Object {
								column: 2
								index: 19
								line: 3
							}
							start: Object {
								column: 1
								index: 18
								line: 3
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "b"
							loc: Object {
								filename: "es2015/uncategorised/394/input.js"
								identifierName: "b"
								end: Object {
									column: 4
									index: 21
									line: 3
								}
								start: Object {
									column: 3
									index: 20
									line: 3
								}
							}
						}
						loc: Object {
							filename: "es2015/uncategorised/394/input.js"
							identifierName: "b"
							end: Object {
								column: 4
								index: 21
								line: 3
							}
							start: Object {
								column: 3
								index: 20
								line: 3
							}
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/394/input.js"
				end: Object {
					column: 14
					index: 43
					line: 4
				}
				start: Object {
					column: 0
					index: 29
					line: 4
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/uncategorised/394/input.js"
					end: Object {
						column: 13
						index: 42
						line: 4
					}
					start: Object {
						column: 0
						index: 29
						line: 4
					}
				}
				right: JSObjectExpression {
					properties: Array []
					loc: Object {
						filename: "es2015/uncategorised/394/input.js"
						end: Object {
							column: 13
							index: 42
							line: 4
						}
						start: Object {
							column: 11
							index: 40
							line: 4
						}
					}
				}
				left: JSMemberExpression {
					loc: Object {
						filename: "es2015/uncategorised/394/input.js"
						end: Object {
							column: 7
							index: 36
							line: 4
						}
						start: Object {
							column: 1
							index: 30
							line: 4
						}
					}
					object: JSReferenceIdentifier {
						name: "a"
						loc: Object {
							filename: "es2015/uncategorised/394/input.js"
							identifierName: "a"
							end: Object {
								column: 2
								index: 31
								line: 4
							}
							start: Object {
								column: 1
								index: 30
								line: 4
							}
						}
					}
					property: JSComputedMemberProperty {
						value: JSStringLiteral {
							value: "c"
							loc: Object {
								filename: "es2015/uncategorised/394/input.js"
								end: Object {
									column: 6
									index: 35
									line: 4
								}
								start: Object {
									column: 3
									index: 32
									line: 4
								}
							}
						}
						loc: Object {
							filename: "es2015/uncategorised/394/input.js"
							end: Object {
								column: 7
								index: 36
								line: 4
							}
							start: Object {
								column: 2
								index: 31
								line: 4
							}
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 es2015/uncategorised/394/input.js:2:1 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid parenthesized binding

    1 │ var a;
  > 2 │ (a) = {};
      │  ^
    3 │ (a.b) = {};
    4 │ (a['c']) = {};

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```