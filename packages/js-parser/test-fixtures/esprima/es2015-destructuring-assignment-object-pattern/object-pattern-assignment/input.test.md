# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-destructuring-assignment-object-pattern > object-pattern-assignment`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
		end: Object {
			column: 0
			index: 86
			line: 9
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
				filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
				end: Object {
					column: 7
					index: 85
					line: 8
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
					end: Object {
						column: 5
						index: 83
						line: 8
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
						end: Object {
							column: 5
							index: 83
							line: 8
						}
						start: Object {
							column: 4
							index: 82
							line: 8
						}
					}
				}
				left: JSAssignmentObjectPattern {
					rest: undefined
					loc: Object {
						filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
						end: Object {
							column: 1
							index: 79
							line: 8
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
					properties: Array [
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 5
											index: 8
											line: 2
										}
										start: Object {
											column: 4
											index: 7
											line: 2
										}
									}
								}
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 5
										index: 8
										line: 2
									}
									start: Object {
										column: 4
										index: 7
										line: 2
									}
								}
							}
							value: JSAssignmentIdentifier {
								name: "a"
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									identifierName: "a"
									end: Object {
										column: 5
										index: 8
										line: 2
									}
									start: Object {
										column: 4
										index: 7
										line: 2
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
								end: Object {
									column: 5
									index: 8
									line: 2
								}
								start: Object {
									column: 4
									index: 7
									line: 2
								}
							}
						}
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 5
											index: 15
											line: 3
										}
										start: Object {
											column: 4
											index: 14
											line: 3
										}
									}
								}
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 5
										index: 15
										line: 3
									}
									start: Object {
										column: 4
										index: 14
										line: 3
									}
								}
							}
							value: JSAssignmentIdentifier {
								name: "a"
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									identifierName: "a"
									end: Object {
										column: 7
										index: 17
										line: 3
									}
									start: Object {
										column: 6
										index: 16
										line: 3
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
								end: Object {
									column: 7
									index: 17
									line: 3
								}
								start: Object {
									column: 4
									index: 14
									line: 3
								}
							}
						}
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 5
											index: 24
											line: 4
										}
										start: Object {
											column: 4
											index: 23
											line: 4
										}
									}
								}
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 5
										index: 24
										line: 4
									}
									start: Object {
										column: 4
										index: 23
										line: 4
									}
								}
							}
							value: JSAssignmentAssignmentPattern {
								operator: "="
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 9
										index: 28
										line: 4
									}
									start: Object {
										column: 6
										index: 25
										line: 4
									}
								}
								left: JSAssignmentIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 7
											index: 26
											line: 4
										}
										start: Object {
											column: 6
											index: 25
											line: 4
										}
									}
								}
								right: JSReferenceIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 9
											index: 28
											line: 4
										}
										start: Object {
											column: 8
											index: 27
											line: 4
										}
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
								end: Object {
									column: 9
									index: 28
									line: 4
								}
								start: Object {
									column: 4
									index: 23
									line: 4
								}
							}
						}
						JSAssignmentObjectPatternProperty {
							key: JSComputedPropertyKey {
								value: JSReferenceIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 6
											index: 36
											line: 5
										}
										start: Object {
											column: 5
											index: 35
											line: 5
										}
									}
								}
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 7
										index: 37
										line: 5
									}
									start: Object {
										column: 4
										index: 34
										line: 5
									}
								}
							}
							value: JSAssignmentObjectPattern {
								rest: undefined
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 11
										index: 41
										line: 5
									}
									start: Object {
										column: 8
										index: 38
										line: 5
									}
								}
								properties: Array [
									JSAssignmentObjectPatternProperty {
										key: JSStaticPropertyKey {
											value: JSIdentifier {
												name: "a"
												loc: Object {
													filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
													identifierName: "a"
													end: Object {
														column: 10
														index: 40
														line: 5
													}
													start: Object {
														column: 9
														index: 39
														line: 5
													}
												}
											}
											loc: Object {
												filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
												end: Object {
													column: 10
													index: 40
													line: 5
												}
												start: Object {
													column: 9
													index: 39
													line: 5
												}
											}
										}
										value: JSAssignmentIdentifier {
											name: "a"
											loc: Object {
												filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
												identifierName: "a"
												end: Object {
													column: 10
													index: 40
													line: 5
												}
												start: Object {
													column: 9
													index: 39
													line: 5
												}
											}
										}
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
											end: Object {
												column: 10
												index: 40
												line: 5
											}
											start: Object {
												column: 9
												index: 39
												line: 5
											}
										}
									}
								]
							}
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
								end: Object {
									column: 11
									index: 41
									line: 5
								}
								start: Object {
									column: 4
									index: 34
									line: 5
								}
							}
						}
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 5
											index: 48
											line: 6
										}
										start: Object {
											column: 4
											index: 47
											line: 6
										}
									}
								}
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 5
										index: 48
										line: 6
									}
									start: Object {
										column: 4
										index: 47
										line: 6
									}
								}
							}
							value: JSMemberExpression {
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 20
										index: 63
										line: 6
									}
									start: Object {
										column: 6
										index: 49
										line: 6
									}
								}
								property: JSComputedMemberProperty {
									value: JSReferenceIdentifier {
										name: "a"
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
											identifierName: "a"
											end: Object {
												column: 19
												index: 62
												line: 6
											}
											start: Object {
												column: 18
												index: 61
												line: 6
											}
										}
									}
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										end: Object {
											column: 20
											index: 63
											line: 6
										}
										start: Object {
											column: 17
											index: 60
											line: 6
										}
									}
								}
								object: JSCallExpression {
									arguments: Array []
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										end: Object {
											column: 17
											index: 60
											line: 6
										}
										start: Object {
											column: 6
											index: 49
											line: 6
										}
									}
									callee: JSReferenceIdentifier {
										name: "some_call"
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
											identifierName: "some_call"
											end: Object {
												column: 15
												index: 58
												line: 6
											}
											start: Object {
												column: 6
												index: 49
												line: 6
											}
										}
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
								end: Object {
									column: 20
									index: 63
									line: 6
								}
								start: Object {
									column: 4
									index: 47
									line: 6
								}
							}
						}
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "a"
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 5
											index: 70
											line: 7
										}
										start: Object {
											column: 4
											index: 69
											line: 7
										}
									}
								}
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 5
										index: 70
										line: 7
									}
									start: Object {
										column: 4
										index: 69
										line: 7
									}
								}
							}
							value: JSMemberExpression {
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
									end: Object {
										column: 12
										index: 77
										line: 7
									}
									start: Object {
										column: 6
										index: 71
										line: 7
									}
								}
								object: JSThisExpression {
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										end: Object {
											column: 10
											index: 75
											line: 7
										}
										start: Object {
											column: 6
											index: 71
											line: 7
										}
									}
								}
								property: JSStaticMemberProperty {
									value: JSIdentifier {
										name: "a"
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
											identifierName: "a"
											end: Object {
												column: 12
												index: 77
												line: 7
											}
											start: Object {
												column: 11
												index: 76
												line: 7
											}
										}
									}
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
										identifierName: "a"
										end: Object {
											column: 12
											index: 77
											line: 7
										}
										start: Object {
											column: 11
											index: 76
											line: 7
										}
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-object-pattern/object-pattern-assignment/input.js"
								end: Object {
									column: 12
									index: 77
									line: 7
								}
								start: Object {
									column: 4
									index: 69
									line: 7
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

### `diagnostics`

```
✔ No known problems!

```