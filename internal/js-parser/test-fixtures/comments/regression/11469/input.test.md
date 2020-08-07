# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `comments > regression > 11469`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "comments/regression/11469/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "comments/regression/11469/input.js"
		end: Object {
			column: 0
			line: 19
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " this.member = 'value';"
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 29
					line: 3
				}
				start: Object {
					column: 4
					line: 3
				}
			}
		}
		CommentBlock {
			id: "1"
			value: " Trailing comment "
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 24
					line: 6
				}
				start: Object {
					column: 2
					line: 6
				}
			}
		}
		CommentLine {
			id: "2"
			value: " this.member = 'value';"
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 29
					line: 11
				}
				start: Object {
					column: 4
					line: 11
				}
			}
		}
		CommentLine {
			id: "3"
			value: " this.member = 'value';"
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 27
					line: 17
				}
				start: Object {
					column: 2
					line: 17
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "comments/regression/11469/input.js"
					identifierName: "A"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 1
					line: 7
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "comments/regression/11469/input.js"
					end: Object {
						column: 1
						line: 7
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: Object {
									filename: "comments/regression/11469/input.js"
									identifierName: "test"
									end: Object {
										column: 6
										line: 2
									}
									start: Object {
										column: 2
										line: 2
									}
								}
							}
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 6
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
						trailingComments: Array ["1"]
						loc: Object {
							filename: "comments/regression/11469/input.js"
							end: Object {
								column: 3
								line: 4
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							trailingComments: undefined
							innerComments: Array ["0"]
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 3
									line: 4
								}
								start: Object {
									column: 9
									line: 2
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
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 8
									line: 2
								}
								start: Object {
									column: 6
									line: 2
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 2
							}
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 6
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
					}
				]
			}
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "B"
				loc: Object {
					filename: "comments/regression/11469/input.js"
					identifierName: "B"
					end: Object {
						column: 7
						line: 9
					}
					start: Object {
						column: 6
						line: 9
					}
				}
			}
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 1
					line: 13
				}
				start: Object {
					column: 0
					line: 9
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "comments/regression/11469/input.js"
					end: Object {
						column: 1
						line: 13
					}
					start: Object {
						column: 0
						line: 9
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: Object {
									filename: "comments/regression/11469/input.js"
									identifierName: "test"
									end: Object {
										column: 6
										line: 10
									}
									start: Object {
										column: 2
										line: 10
									}
								}
							}
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 6
									line: 10
								}
								start: Object {
									column: 2
									line: 10
								}
							}
						}
						loc: Object {
							filename: "comments/regression/11469/input.js"
							end: Object {
								column: 3
								line: 12
							}
							start: Object {
								column: 2
								line: 10
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							trailingComments: Array []
							innerComments: Array ["2"]
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 3
									line: 12
								}
								start: Object {
									column: 9
									line: 10
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
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 8
									line: 10
								}
								start: Object {
									column: 6
									line: 10
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 10
							}
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 6
									line: 10
								}
								start: Object {
									column: 2
									line: 10
								}
							}
						}
					}
				]
			}
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "comments/regression/11469/input.js"
					identifierName: "C"
					end: Object {
						column: 7
						line: 15
					}
					start: Object {
						column: 6
						line: 15
					}
				}
			}
			loc: Object {
				filename: "comments/regression/11469/input.js"
				end: Object {
					column: 1
					line: 18
				}
				start: Object {
					column: 0
					line: 15
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "comments/regression/11469/input.js"
					end: Object {
						column: 1
						line: 18
					}
					start: Object {
						column: 0
						line: 15
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "test"
								loc: Object {
									filename: "comments/regression/11469/input.js"
									identifierName: "test"
									end: Object {
										column: 6
										line: 16
									}
									start: Object {
										column: 2
										line: 16
									}
								}
							}
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 6
									line: 16
								}
								start: Object {
									column: 2
									line: 16
								}
							}
						}
						trailingComments: Array ["3"]
						loc: Object {
							filename: "comments/regression/11469/input.js"
							end: Object {
								column: 11
								line: 16
							}
							start: Object {
								column: 2
								line: 16
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							trailingComments: undefined
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 11
									line: 16
								}
								start: Object {
									column: 9
									line: 16
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
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 8
									line: 16
								}
								start: Object {
									column: 6
									line: 16
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 16
							}
							loc: Object {
								filename: "comments/regression/11469/input.js"
								end: Object {
									column: 6
									line: 16
								}
								start: Object {
									column: 2
									line: 16
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