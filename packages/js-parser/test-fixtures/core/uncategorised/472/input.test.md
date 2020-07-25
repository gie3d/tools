# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 472`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "core/uncategorised/472/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/472/input.js"
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
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						"eval"
						RAW_MARKUP {value: " is a reserved word"}
					]
				}
			}
			location: Object {
				filename: "core/uncategorised/472/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 36
					index: 36
					line: 1
				}
				start: Object {
					column: 32
					index: 32
					line: 1
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "hello"
				loc: Object {
					filename: "core/uncategorised/472/input.js"
					identifierName: "hello"
					end: Object {
						column: 14
						index: 14
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
				filename: "core/uncategorised/472/input.js"
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
					filename: "core/uncategorised/472/input.js"
					end: Object {
						column: 16
						index: 16
						line: 1
					}
					start: Object {
						column: 14
						index: 14
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				loc: Object {
					filename: "core/uncategorised/472/input.js"
					end: Object {
						column: 44
						index: 44
						line: 1
					}
					start: Object {
						column: 17
						index: 17
						line: 1
					}
				}
				directives: Array [
					JSDirective {
						value: "use strict"
						loc: Object {
							filename: "core/uncategorised/472/input.js"
							end: Object {
								column: 31
								index: 31
								line: 1
							}
							start: Object {
								column: 18
								index: 18
								line: 1
							}
						}
					}
				]
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "core/uncategorised/472/input.js"
							end: Object {
								column: 42
								index: 42
								line: 1
							}
							start: Object {
								column: 32
								index: 32
								line: 1
							}
						}
						expression: JSAssignmentExpression {
							operator: "="
							loc: Object {
								filename: "core/uncategorised/472/input.js"
								end: Object {
									column: 41
									index: 41
									line: 1
								}
								start: Object {
									column: 32
									index: 32
									line: 1
								}
							}
							left: JSAssignmentIdentifier {
								name: "eval"
								loc: Object {
									filename: "core/uncategorised/472/input.js"
									identifierName: "eval"
									end: Object {
										column: 36
										index: 36
										line: 1
									}
									start: Object {
										column: 32
										index: 32
										line: 1
									}
								}
							}
							right: JSNumericLiteral {
								value: 10
								format: undefined
								loc: Object {
									filename: "core/uncategorised/472/input.js"
									end: Object {
										column: 41
										index: 41
										line: 1
									}
									start: Object {
										column: 39
										index: 39
										line: 1
									}
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

 core/uncategorised/472/input.js:1:32 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ eval is a reserved word

    function hello() {'use strict'; eval = 10; }
                                    ^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```