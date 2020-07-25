# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0270`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/invalid-syntax/migrated_0270/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/invalid-syntax/migrated_0270/input.js"
		end: Object {
			column: 0
			index: 31
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
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Classes may not have static property named prototype"}]}
			}
			location: Object {
				filename: "esprima/invalid-syntax/migrated_0270/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 25
					index: 25
					line: 1
				}
				start: Object {
					column: 16
					index: 16
					line: 1
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0270/input.js"
					identifierName: "A"
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
			loc: Object {
				filename: "esprima/invalid-syntax/migrated_0270/input.js"
				end: Object {
					column: 30
					index: 30
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0270/input.js"
					end: Object {
						column: 30
						index: 30
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "prototype"
								loc: Object {
									filename: "esprima/invalid-syntax/migrated_0270/input.js"
									identifierName: "prototype"
									end: Object {
										column: 25
										index: 25
										line: 1
									}
									start: Object {
										column: 16
										index: 16
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0270/input.js"
								end: Object {
									column: 25
									index: 25
									line: 1
								}
								start: Object {
									column: 16
									index: 16
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0270/input.js"
							end: Object {
								column: 29
								index: 29
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0270/input.js"
								end: Object {
									column: 29
									index: 29
									line: 1
								}
								start: Object {
									column: 27
									index: 27
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0270/input.js"
								end: Object {
									column: 27
									index: 27
									line: 1
								}
								start: Object {
									column: 25
									index: 25
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 9
								index: 9
								line: 1
							}
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0270/input.js"
								end: Object {
									column: 25
									index: 25
									line: 1
								}
								start: Object {
									column: 9
									index: 9
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

 esprima/invalid-syntax/migrated_0270/input.js:1:16 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Classes may not have static property named prototype

    class A {static prototype(){}}
                    ^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```