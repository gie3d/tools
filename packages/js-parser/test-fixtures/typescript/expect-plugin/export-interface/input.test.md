# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > expect-plugin > export-interface`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "typescript/expect-plugin/export-interface/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "typescript/expect-plugin/export-interface/input.js"
		end: Object {
			column: 0
			index: 24
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
			location: Object {
				filename: "typescript/expect-plugin/export-interface/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 7
					index: 7
					line: 1
				}
				start: Object {
					column: 7
					index: 7
					line: 1
				}
			}
			description: Object {
				category: "parse/js"
				advice: Array [
					log {
						category: "info"
						text: MARKUP {parts: Array [RAW_MARKUP {value: "To enable <emphasis>TypeScript</emphasis> support, the file extension should end in <emphasis>.ts</emphasis> or <emphasis>.tsx</emphasis>"}]}
					}
				]
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "A "}
						"interface declaration"
						RAW_MARKUP {value: " is only valid inside of a TypeScript file"}
					]
				}
			}
		}
	]
	body: Array [
		JSExportLocalDeclaration {
			exportKind: "type"
			specifiers: undefined
			loc: Object {
				filename: "typescript/expect-plugin/export-interface/input.js"
				end: Object {
					column: 23
					index: 23
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: TSInterfaceDeclaration {
				id: JSBindingIdentifier {
					name: "Foo"
					loc: Object {
						filename: "typescript/expect-plugin/export-interface/input.js"
						identifierName: "Foo"
						end: Object {
							column: 20
							index: 20
							line: 1
						}
						start: Object {
							column: 17
							index: 17
							line: 1
						}
					}
				}
				extends: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/expect-plugin/export-interface/input.js"
					end: Object {
						column: 23
						index: 23
						line: 1
					}
					start: Object {
						column: 7
						index: 7
						line: 1
					}
				}
				body: TSInterfaceBody {
					body: Array []
					loc: Object {
						filename: "typescript/expect-plugin/export-interface/input.js"
						end: Object {
							column: 23
							index: 23
							line: 1
						}
						start: Object {
							column: 21
							index: 21
							line: 1
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

 typescript/expect-plugin/export-interface/input.js:1:7 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ A interface declaration is only valid inside of a TypeScript file

    export interface Foo {}
           ^

  ℹ To enable TypeScript support, the file extension should end in .ts or .tsx

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```