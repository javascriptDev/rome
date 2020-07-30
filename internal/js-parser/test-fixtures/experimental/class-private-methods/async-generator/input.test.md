# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-methods > async-generator`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/class-private-methods/async-generator/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/class-private-methods/async-generator/input.js"
		end: Object {
			column: 0
			index: 213
			line: 14
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "experimental/class-private-methods/async-generator/input.js"
					identifierName: "Foo"
					end: Object {
						column: 9
						index: 9
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
				filename: "experimental/class-private-methods/async-generator/input.js"
				end: Object {
					column: 1
					index: 212
					line: 13
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
					filename: "experimental/class-private-methods/async-generator/input.js"
					end: Object {
						column: 1
						index: 212
						line: 13
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassPrivateMethod {
						kind: "method"
						key: JSPrivateName {
							id: JSIdentifier {
								name: "readLines"
								loc: Object {
									filename: "experimental/class-private-methods/async-generator/input.js"
									identifierName: "readLines"
									end: Object {
										column: 19
										index: 31
										line: 2
									}
									start: Object {
										column: 10
										index: 22
										line: 2
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-methods/async-generator/input.js"
								end: Object {
									column: 19
									index: 31
									line: 2
								}
								start: Object {
									column: 9
									index: 21
									line: 2
								}
							}
						}
						loc: Object {
							filename: "experimental/class-private-methods/async-generator/input.js"
							end: Object {
								column: 3
								index: 210
								line: 12
							}
							start: Object {
								column: 2
								index: 14
								line: 2
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
								index: 14
								line: 2
							}
							loc: Object {
								filename: "experimental/class-private-methods/async-generator/input.js"
								end: Object {
									column: 19
									index: 31
									line: 2
								}
								start: Object {
									column: 2
									index: 14
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: true
							generator: true
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "experimental/class-private-methods/async-generator/input.js"
								end: Object {
									column: 25
									index: 37
									line: 2
								}
								start: Object {
									column: 19
									index: 31
									line: 2
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "path"
									loc: Object {
										filename: "experimental/class-private-methods/async-generator/input.js"
										identifierName: "path"
										end: Object {
											column: 24
											index: 36
											line: 2
										}
										start: Object {
											column: 20
											index: 32
											line: 2
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "experimental/class-private-methods/async-generator/input.js"
											end: Object {
												column: 24
												index: 36
												line: 2
											}
											start: Object {
												column: 20
												index: 32
												line: 2
											}
										}
									}
								}
							]
						}
						body: JSBlockStatement {
							directives: Array []
							loc: Object {
								filename: "experimental/class-private-methods/async-generator/input.js"
								end: Object {
									column: 3
									index: 210
									line: 12
								}
								start: Object {
									column: 26
									index: 38
									line: 2
								}
							}
							body: Array [
								JSVariableDeclarationStatement {
									loc: Object {
										filename: "experimental/class-private-methods/async-generator/input.js"
										end: Object {
											column: 36
											index: 76
											line: 3
										}
										start: Object {
											column: 4
											index: 44
											line: 3
										}
									}
									declaration: JSVariableDeclaration {
										kind: "let"
										loc: Object {
											filename: "experimental/class-private-methods/async-generator/input.js"
											end: Object {
												column: 36
												index: 76
												line: 3
											}
											start: Object {
												column: 4
												index: 44
												line: 3
											}
										}
										declarations: Array [
											JSVariableDeclarator {
												id: JSBindingIdentifier {
													name: "file"
													loc: Object {
														filename: "experimental/class-private-methods/async-generator/input.js"
														identifierName: "file"
														end: Object {
															column: 12
															index: 52
															line: 3
														}
														start: Object {
															column: 8
															index: 48
															line: 3
														}
													}
												}
												loc: Object {
													filename: "experimental/class-private-methods/async-generator/input.js"
													end: Object {
														column: 35
														index: 75
														line: 3
													}
													start: Object {
														column: 8
														index: 48
														line: 3
													}
												}
												init: JSAwaitExpression {
													loc: Object {
														filename: "experimental/class-private-methods/async-generator/input.js"
														end: Object {
															column: 35
															index: 75
															line: 3
														}
														start: Object {
															column: 15
															index: 55
															line: 3
														}
													}
													argument: JSCallExpression {
														loc: Object {
															filename: "experimental/class-private-methods/async-generator/input.js"
															end: Object {
																column: 35
																index: 75
																line: 3
															}
															start: Object {
																column: 21
																index: 61
																line: 3
															}
														}
														callee: JSReferenceIdentifier {
															name: "fileOpen"
															loc: Object {
																filename: "experimental/class-private-methods/async-generator/input.js"
																identifierName: "fileOpen"
																end: Object {
																	column: 29
																	index: 69
																	line: 3
																}
																start: Object {
																	column: 21
																	index: 61
																	line: 3
																}
															}
														}
														arguments: Array [
															JSReferenceIdentifier {
																name: "path"
																loc: Object {
																	filename: "experimental/class-private-methods/async-generator/input.js"
																	identifierName: "path"
																	end: Object {
																		column: 34
																		index: 74
																		line: 3
																	}
																	start: Object {
																		column: 30
																		index: 70
																		line: 3
																	}
																}
															}
														]
													}
												}
											}
										]
									}
								}
								JSTryStatement {
									handler: undefined
									loc: Object {
										filename: "experimental/class-private-methods/async-generator/input.js"
										end: Object {
											column: 5
											index: 206
											line: 11
										}
										start: Object {
											column: 4
											index: 82
											line: 5
										}
									}
									finalizer: JSBlockStatement {
										directives: Array []
										loc: Object {
											filename: "experimental/class-private-methods/async-generator/input.js"
											end: Object {
												column: 5
												index: 206
												line: 11
											}
											start: Object {
												column: 14
												index: 173
												line: 9
											}
										}
										body: Array [
											JSExpressionStatement {
												loc: Object {
													filename: "experimental/class-private-methods/async-generator/input.js"
													end: Object {
														column: 25
														index: 200
														line: 10
													}
													start: Object {
														column: 6
														index: 181
														line: 10
													}
												}
												expression: JSAwaitExpression {
													loc: Object {
														filename: "experimental/class-private-methods/async-generator/input.js"
														end: Object {
															column: 24
															index: 199
															line: 10
														}
														start: Object {
															column: 6
															index: 181
															line: 10
														}
													}
													argument: JSCallExpression {
														arguments: Array []
														loc: Object {
															filename: "experimental/class-private-methods/async-generator/input.js"
															end: Object {
																column: 24
																index: 199
																line: 10
															}
															start: Object {
																column: 12
																index: 187
																line: 10
															}
														}
														callee: JSMemberExpression {
															loc: Object {
																filename: "experimental/class-private-methods/async-generator/input.js"
																end: Object {
																	column: 22
																	index: 197
																	line: 10
																}
																start: Object {
																	column: 12
																	index: 187
																	line: 10
																}
															}
															object: JSReferenceIdentifier {
																name: "file"
																loc: Object {
																	filename: "experimental/class-private-methods/async-generator/input.js"
																	identifierName: "file"
																	end: Object {
																		column: 16
																		index: 191
																		line: 10
																	}
																	start: Object {
																		column: 12
																		index: 187
																		line: 10
																	}
																}
															}
															property: JSStaticMemberProperty {
																value: JSIdentifier {
																	name: "close"
																	loc: Object {
																		filename: "experimental/class-private-methods/async-generator/input.js"
																		identifierName: "close"
																		end: Object {
																			column: 22
																			index: 197
																			line: 10
																		}
																		start: Object {
																			column: 17
																			index: 192
																			line: 10
																		}
																	}
																}
																loc: Object {
																	filename: "experimental/class-private-methods/async-generator/input.js"
																	identifierName: "close"
																	end: Object {
																		column: 22
																		index: 197
																		line: 10
																	}
																	start: Object {
																		column: 17
																		index: 192
																		line: 10
																	}
																}
															}
														}
													}
												}
											}
										]
									}
									block: JSBlockStatement {
										directives: Array []
										loc: Object {
											filename: "experimental/class-private-methods/async-generator/input.js"
											end: Object {
												column: 5
												index: 164
												line: 9
											}
											start: Object {
												column: 8
												index: 86
												line: 5
											}
										}
										body: Array [
											JSWhileStatement {
												loc: Object {
													filename: "experimental/class-private-methods/async-generator/input.js"
													end: Object {
														column: 7
														index: 158
														line: 8
													}
													start: Object {
														column: 6
														index: 94
														line: 6
													}
												}
												test: JSUnaryExpression {
													operator: "!"
													prefix: true
													loc: Object {
														filename: "experimental/class-private-methods/async-generator/input.js"
														end: Object {
															column: 22
															index: 110
															line: 6
														}
														start: Object {
															column: 13
															index: 101
															line: 6
														}
													}
													argument: JSMemberExpression {
														loc: Object {
															filename: "experimental/class-private-methods/async-generator/input.js"
															end: Object {
																column: 22
																index: 110
																line: 6
															}
															start: Object {
																column: 14
																index: 102
																line: 6
															}
														}
														object: JSReferenceIdentifier {
															name: "file"
															loc: Object {
																filename: "experimental/class-private-methods/async-generator/input.js"
																identifierName: "file"
																end: Object {
																	column: 18
																	index: 106
																	line: 6
																}
																start: Object {
																	column: 14
																	index: 102
																	line: 6
																}
															}
														}
														property: JSStaticMemberProperty {
															value: JSIdentifier {
																name: "EOF"
																loc: Object {
																	filename: "experimental/class-private-methods/async-generator/input.js"
																	identifierName: "EOF"
																	end: Object {
																		column: 22
																		index: 110
																		line: 6
																	}
																	start: Object {
																		column: 19
																		index: 107
																		line: 6
																	}
																}
															}
															loc: Object {
																filename: "experimental/class-private-methods/async-generator/input.js"
																identifierName: "EOF"
																end: Object {
																	column: 22
																	index: 110
																	line: 6
																}
																start: Object {
																	column: 19
																	index: 107
																	line: 6
																}
															}
														}
													}
												}
												body: JSBlockStatement {
													directives: Array []
													loc: Object {
														filename: "experimental/class-private-methods/async-generator/input.js"
														end: Object {
															column: 7
															index: 158
															line: 8
														}
														start: Object {
															column: 24
															index: 112
															line: 6
														}
													}
													body: Array [
														JSExpressionStatement {
															loc: Object {
																filename: "experimental/class-private-methods/async-generator/input.js"
																end: Object {
																	column: 36
																	index: 150
																	line: 7
																}
																start: Object {
																	column: 8
																	index: 122
																	line: 7
																}
															}
															expression: JSYieldExpression {
																delegate: false
																loc: Object {
																	filename: "experimental/class-private-methods/async-generator/input.js"
																	end: Object {
																		column: 35
																		index: 149
																		line: 7
																	}
																	start: Object {
																		column: 8
																		index: 122
																		line: 7
																	}
																}
																argument: JSAwaitExpression {
																	loc: Object {
																		filename: "experimental/class-private-methods/async-generator/input.js"
																		end: Object {
																			column: 35
																			index: 149
																			line: 7
																		}
																		start: Object {
																			column: 14
																			index: 128
																			line: 7
																		}
																	}
																	argument: JSCallExpression {
																		arguments: Array []
																		loc: Object {
																			filename: "experimental/class-private-methods/async-generator/input.js"
																			end: Object {
																				column: 35
																				index: 149
																				line: 7
																			}
																			start: Object {
																				column: 20
																				index: 134
																				line: 7
																			}
																		}
																		callee: JSMemberExpression {
																			loc: Object {
																				filename: "experimental/class-private-methods/async-generator/input.js"
																				end: Object {
																					column: 33
																					index: 147
																					line: 7
																				}
																				start: Object {
																					column: 20
																					index: 134
																					line: 7
																				}
																			}
																			object: JSReferenceIdentifier {
																				name: "file"
																				loc: Object {
																					filename: "experimental/class-private-methods/async-generator/input.js"
																					identifierName: "file"
																					end: Object {
																						column: 24
																						index: 138
																						line: 7
																					}
																					start: Object {
																						column: 20
																						index: 134
																						line: 7
																					}
																				}
																			}
																			property: JSStaticMemberProperty {
																				value: JSIdentifier {
																					name: "readLine"
																					loc: Object {
																						filename: "experimental/class-private-methods/async-generator/input.js"
																						identifierName: "readLine"
																						end: Object {
																							column: 33
																							index: 147
																							line: 7
																						}
																						start: Object {
																							column: 25
																							index: 139
																							line: 7
																						}
																					}
																				}
																				loc: Object {
																					filename: "experimental/class-private-methods/async-generator/input.js"
																					identifierName: "readLine"
																					end: Object {
																						column: 33
																						index: 147
																						line: 7
																					}
																					start: Object {
																						column: 25
																						index: 139
																						line: 7
																					}
																				}
																			}
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
								}
							]
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