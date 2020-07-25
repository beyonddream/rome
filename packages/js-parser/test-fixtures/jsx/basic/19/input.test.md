# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > 19`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "jsx/basic/19/input.jsx"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array ["jsx"]
	loc: Object {
		filename: "jsx/basic/19/input.jsx"
		end: Object {
			column: 53
			index: 53
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "jsx/basic/19/input.jsx"
				end: Object {
					column: 53
					index: 53
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSXElement {
				name: JSXIdentifier {
					name: "div"
					loc: Object {
						filename: "jsx/basic/19/input.jsx"
						end: Object {
							column: 4
							index: 4
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
				}
				children: Array []
				selfClosing: false
				typeArguments: undefined
				loc: Object {
					filename: "jsx/basic/19/input.jsx"
					end: Object {
						column: 53
						index: 53
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				attributes: Array [
					JSXAttribute {
						name: JSXIdentifier {
							name: "pre"
							loc: Object {
								filename: "jsx/basic/19/input.jsx"
								end: Object {
									column: 8
									index: 8
									line: 1
								}
								start: Object {
									column: 5
									index: 5
									line: 1
								}
							}
						}
						value: JSStringLiteral {
							value: "leading"
							loc: Object {
								filename: "jsx/basic/19/input.jsx"
								end: Object {
									column: 18
									index: 18
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
							filename: "jsx/basic/19/input.jsx"
							end: Object {
								column: 18
								index: 18
								line: 1
							}
							start: Object {
								column: 5
								index: 5
								line: 1
							}
						}
					}
					JSXAttribute {
						name: JSXIdentifier {
							name: "pre2"
							loc: Object {
								filename: "jsx/basic/19/input.jsx"
								end: Object {
									column: 23
									index: 23
									line: 1
								}
								start: Object {
									column: 19
									index: 19
									line: 1
								}
							}
						}
						value: JSStringLiteral {
							value: "attribute"
							loc: Object {
								filename: "jsx/basic/19/input.jsx"
								end: Object {
									column: 35
									index: 35
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
							filename: "jsx/basic/19/input.jsx"
							end: Object {
								column: 35
								index: 35
								line: 1
							}
							start: Object {
								column: 19
								index: 19
								line: 1
							}
						}
					}
					JSXSpreadAttribute {
						loc: Object {
							filename: "jsx/basic/19/input.jsx"
							end: Object {
								column: 46
								index: 46
								line: 1
							}
							start: Object {
								column: 36
								index: 36
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "props"
							loc: Object {
								filename: "jsx/basic/19/input.jsx"
								identifierName: "props"
								end: Object {
									column: 45
									index: 45
									line: 1
								}
								start: Object {
									column: 40
									index: 40
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

### `diagnostics`

```
✔ No known problems!

```