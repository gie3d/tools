# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-generator > generator-declaration-with-yield-delegate`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
		end: Object {
			column: 0
			index: 30
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "foo"
				loc: Object {
					filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
					identifierName: "foo"
					end: Object {
						column: 13
						index: 13
						line: 1
					}
					start: Object {
						column: 10
						index: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
				end: Object {
					column: 29
					index: 29
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
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
					end: Object {
						column: 15
						index: 15
						line: 1
					}
					start: Object {
						column: 13
						index: 13
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
					end: Object {
						column: 29
						index: 29
						line: 1
					}
					start: Object {
						column: 16
						index: 16
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
							end: Object {
								column: 27
								index: 27
								line: 1
							}
							start: Object {
								column: 18
								index: 18
								line: 1
							}
						}
						expression: JSYieldExpression {
							delegate: true
							loc: Object {
								filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
								end: Object {
									column: 26
									index: 26
									line: 1
								}
								start: Object {
									column: 18
									index: 18
									line: 1
								}
							}
							argument: JSNumericLiteral {
								value: 3
								format: undefined
								loc: Object {
									filename: "esprima/es2015-generator/generator-declaration-with-yield-delegate/input.js"
									end: Object {
										column: 26
										index: 26
										line: 1
									}
									start: Object {
										column: 25
										index: 25
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
✔ No known problems!

```