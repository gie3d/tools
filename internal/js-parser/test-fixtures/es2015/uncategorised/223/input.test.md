# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 223`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/uncategorised/223/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/223/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Object pattern cannot contains methods"}]}
			}
			location: Object {
				filename: "es2015/uncategorised/223/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 8
					line: 1
				}
				start: Object {
					column: 7
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/223/input.js"
				end: Object {
					column: 20
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/uncategorised/223/input.js"
					end: Object {
						column: 19
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "es2015/uncategorised/223/input.js"
						end: Object {
							column: 19
							line: 1
						}
						start: Object {
							column: 18
							line: 1
						}
					}
				}
				left: JSAssignmentObjectPattern {
					rest: undefined
					loc: Object {
						filename: "es2015/uncategorised/223/input.js"
						end: Object {
							column: 15
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					properties: Array [
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "X"
									loc: Object {
										filename: "es2015/uncategorised/223/input.js"
										end: Object {
											column: 13
											line: 1
										}
										start: Object {
											column: 3
											line: 1
										}
									}
								}
								loc: Object {
									filename: "es2015/uncategorised/223/input.js"
									end: Object {
										column: 13
										line: 1
									}
									start: Object {
										column: 3
										line: 1
									}
								}
							}
							value: JSAssignmentIdentifier {
								name: "X"
								loc: Object {
									filename: "es2015/uncategorised/223/input.js"
									end: Object {
										column: 13
										line: 1
									}
									start: Object {
										column: 3
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2015/uncategorised/223/input.js"
								end: Object {
									column: 13
									line: 1
								}
								start: Object {
									column: 3
									line: 1
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

 es2015/uncategorised/223/input.js:1:7 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Object pattern cannot contains methods

    ({ get x() {} } = 0)
           ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
