# scroll2-1
scroll1(2.0)
	"deploy": {
		"VM:-": {
			"linkReferences": {},
			"autoDeployLib": true
		},
		"main:1": {
			"linkReferences": {},
			"autoDeployLib": true
		},
		"ropsten:3": {
			"linkReferences": {},
			"autoDeployLib": true
		},
		"rinkeby:4": {
			"linkReferences": {},
			"autoDeployLib": true
		},
		"kovan:42": {
			"linkReferences": {},
			"autoDeployLib": true
		},
		"goerli:5": {
			"linkReferences": {},
			"autoDeployLib": true
		},
		"Custom": {
			"linkReferences": {},
			"autoDeployLib": true
		}
	},
	"data": {
		"bytecode": {
			"functionDebugData": {},
			"generatedSources": [],
			"linkReferences": {},
			"object": "6080604052348015600e575f80fd5b5061014e8061001c5f395ff3fe608060405234801561000f575f80fd5b5060043610610029575f3560e01c806313bdfacd1461002d575b5f80fd5b61003561004b565b60405161004291906100f8565b60405180910390f35b60606040518060400160405280600c81526020017f48656c6c6f20576f726c64210000000000000000000000000000000000000000815250905090565b5f81519050919050565b5f82825260208201905092915050565b8281835e5f83830152505050565b5f601f19601f8301169050919050565b5f6100ca82610088565b6100d48185610092565b93506100e48185602086016100a2565b6100ed816100b0565b840191505092915050565b5f6020820190508181035f83015261011081846100c0565b90509291505056fea2646970667358221220f547b39c1ac7ab00ddd4bcf1b194a40ea7069ecae4ebc5a680097b5072ac06d864736f6c63430008190033",
			"opcodes": "PUSH1 0x80 PUSH1 0x40 MSTORE CALLVALUE DUP1 ISZERO PUSH1 0xE JUMPI PUSH0 DUP1 REVERT JUMPDEST POP PUSH2 0x14E DUP1 PUSH2 0x1C PUSH0 CODECOPY PUSH0 RETURN INVALID PUSH1 0x80 PUSH1 0x40 MSTORE CALLVALUE DUP1 ISZERO PUSH2 0xF JUMPI PUSH0 DUP1 REVERT JUMPDEST POP PUSH1 0x4 CALLDATASIZE LT PUSH2 0x29 JUMPI PUSH0 CALLDATALOAD PUSH1 0xE0 SHR DUP1 PUSH4 0x13BDFACD EQ PUSH2 0x2D JUMPI JUMPDEST PUSH0 DUP1 REVERT JUMPDEST PUSH2 0x35 PUSH2 0x4B JUMP JUMPDEST PUSH1 0x40 MLOAD PUSH2 0x42 SWAP2 SWAP1 PUSH2 0xF8 JUMP JUMPDEST PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST PUSH1 0x60 PUSH1 0x40 MLOAD DUP1 PUSH1 0x40 ADD PUSH1 0x40 MSTORE DUP1 PUSH1 0xC DUP2 MSTORE PUSH1 0x20 ADD PUSH32 0x48656C6C6F20576F726C64210000000000000000000000000000000000000000 DUP2 MSTORE POP SWAP1 POP SWAP1 JUMP JUMPDEST PUSH0 DUP2 MLOAD SWAP1 POP SWAP2 SWAP1 POP JUMP JUMPDEST PUSH0 DUP3 DUP3 MSTORE PUSH1 0x20 DUP3 ADD SWAP1 POP SWAP3 SWAP2 POP POP JUMP JUMPDEST DUP3 DUP2 DUP4 MCOPY PUSH0 DUP4 DUP4 ADD MSTORE POP POP POP JUMP JUMPDEST PUSH0 PUSH1 0x1F NOT PUSH1 0x1F DUP4 ADD AND SWAP1 POP SWAP2 SWAP1 POP JUMP JUMPDEST PUSH0 PUSH2 0xCA DUP3 PUSH2 0x88 JUMP JUMPDEST PUSH2 0xD4 DUP2 DUP6 PUSH2 0x92 JUMP JUMPDEST SWAP4 POP PUSH2 0xE4 DUP2 DUP6 PUSH1 0x20 DUP7 ADD PUSH2 0xA2 JUMP JUMPDEST PUSH2 0xED DUP2 PUSH2 0xB0 JUMP JUMPDEST DUP5 ADD SWAP2 POP POP SWAP3 SWAP2 POP POP JUMP JUMPDEST PUSH0 PUSH1 0x20 DUP3 ADD SWAP1 POP DUP2 DUP2 SUB PUSH0 DUP4 ADD MSTORE PUSH2 0x110 DUP2 DUP5 PUSH2 0xC0 JUMP JUMPDEST SWAP1 POP SWAP3 SWAP2 POP POP JUMP INVALID LOG2 PUSH5 0x6970667358 0x22 SLT KECCAK256 CREATE2 SELFBALANCE 0xB3 SWAP13 BYTE 0xC7 0xAB STOP 0xDD 0xD4 0xBC CALL 0xB1 SWAP5 LOG4 0xE 0xA7 MOD SWAP15 0xCA 0xE4 0xEB 0xC5 0xA6 DUP1 MULMOD PUSH28 0x5072AC06D864736F6C63430008190033000000000000000000000000 ",
			"sourceMap": "66:159:0:-:0;;;;;;;;;;;;;;;;;;;"
		},
		"deployedBytecode": {
			"functionDebugData": {
				"@print_10": {
					"entryPoint": 75,
					"id": 10,
					"parameterSlots": 0,
					"returnSlots": 1
				},
				"abi_encode_t_string_memory_ptr_to_t_string_memory_ptr_fromStack": {
					"entryPoint": 192,
					"id": null,
					"parameterSlots": 2,
					"returnSlots": 1
				},
				"abi_encode_tuple_t_string_memory_ptr__to_t_string_memory_ptr__fromStack_reversed": {
					"entryPoint": 248,
					"id": null,
					"parameterSlots": 2,
					"returnSlots": 1
				},
				"array_length_t_string_memory_ptr": {
					"entryPoint": 136,
					"id": null,
					"parameterSlots": 1,
					"returnSlots": 1
				},
				"array_storeLengthForEncoding_t_string_memory_ptr_fromStack": {
					"entryPoint": 146,
					"id": null,
					"parameterSlots": 2,
					"returnSlots": 1
				},
				"copy_memory_to_memory_with_cleanup": {
					"entryPoint": 162,
					"id": null,
					"parameterSlots": 3,
					"returnSlots": 0
				},
				"round_up_to_mul_of_32": {
					"entryPoint": 176,
					"id": null,
					"parameterSlots": 1,
					"returnSlots": 1
				}
			},
			"generatedSources": [
				{
					"ast": {
						"nativeSrc": "0:1239:1",
						"nodeType": "YulBlock",
						"src": "0:1239:1",
						"statements": [
							{
								"body": {
									"nativeSrc": "66:40:1",
									"nodeType": "YulBlock",
									"src": "66:40:1",
									"statements": [
										{
											"nativeSrc": "77:22:1",
											"nodeType": "YulAssignment",
											"src": "77:22:1",
											"value": {
												"arguments": [
													{
														"name": "value",
														"nativeSrc": "93:5:1",
														"nodeType": "YulIdentifier",
														"src": "93:5:1"
													}
												],
												"functionName": {
													"name": "mload",
													"nativeSrc": "87:5:1",
													"nodeType": "YulIdentifier",
													"src": "87:5:1"
												},
												"nativeSrc": "87:12:1",
												"nodeType": "YulFunctionCall",
												"src": "87:12:1"
											},
											"variableNames": [
												{
													"name": "length",
													"nativeSrc": "77:6:1",
													"nodeType": "YulIdentifier",
													"src": "77:6:1"
												}
											]
										}
									]
								},
								"name": "array_length_t_string_memory_ptr",
								"nativeSrc": "7:99:1",
								"nodeType": "YulFunctionDefinition",
								"parameters": [
									{
										"name": "value",
										"nativeSrc": "49:5:1",
										"nodeType": "YulTypedName",
										"src": "49:5:1",
										"type": ""
									}
								],
								"returnVariables": [
									{
										"name": "length",
										"nativeSrc": "59:6:1",
										"nodeType": "YulTypedName",
										"src": "59:6:1",
										"type": ""
									}
								],
								"src": "7:99:1"
							},
							{
								"body": {
									"nativeSrc": "208:73:1",
									"nodeType": "YulBlock",
									"src": "208:73:1",
									"statements": [
										{
											"expression": {
												"arguments": [
													{
														"name": "pos",
														"nativeSrc": "225:3:1",
														"nodeType": "YulIdentifier",
														"src": "225:3:1"
													},
													{
														"name": "length",
														"nativeSrc": "230:6:1",
														"nodeType": "YulIdentifier",
														"src": "230:6:1"
													}
												],
												"functionName": {
													"name": "mstore",
													"nativeSrc": "218:6:1",
													"nodeType": "YulIdentifier",
													"src": "218:6:1"
												},
												"nativeSrc": "218:19:1",
												"nodeType": "YulFunctionCall",
												"src": "218:19:1"
											},
											"nativeSrc": "218:19:1",
											"nodeType": "YulExpressionStatement",
											"src": "218:19:1"
										},
										{
											"nativeSrc": "246:29:1",
											"nodeType": "YulAssignment",
											"src": "246:29:1",
											"value": {
												"arguments": [
													{
														"name": "pos",
														"nativeSrc": "265:3:1",
														"nodeType": "YulIdentifier",
														"src": "265:3:1"
													},
													{
														"kind": "number",
														"nativeSrc": "270:4:1",
														"nodeType": "YulLiteral",
														"src": "270:4:1",
														"type": "",
														"value": "0x20"
													}
												],
												"functionName": {
													"name": "add",
													"nativeSrc": "261:3:1",
													"nodeType": "YulIdentifier",
													"src": "261:3:1"
												},
												"nativeSrc": "261:14:1",
												"nodeType": "YulFunctionCall",
												"src": "261:14:1"
											},
											"variableNames": [
												{
													"name": "updated_pos",
													"nativeSrc": "246:11:1",
													"nodeType": "YulIdentifier",
													"src": "246:11:1"
												}
											]
										}
									]
								},
								"name": "array_storeLengthForEncoding_t_string_memory_ptr_fromStack",
								"nativeSrc": "112:169:1",
								"nodeType": "YulFunctionDefinition",
								"parameters": [
									{
										"name": "pos",
										"nativeSrc": "180:3:1",
										"nodeType": "YulTypedName",
										"src": "180:3:1",
										"type": ""
									},
									{
										"name": "length",
										"nativeSrc": "185:6:1",
										"nodeType": "YulTypedName",
										"src": "185:6:1",
										"type": ""
									}
								],
								"returnVariables": [
									{
										"name": "updated_pos",
										"nativeSrc": "196:11:1",
										"nodeType": "YulTypedName",
										"src": "196:11:1",
										"type": ""
									}
								],
								"src": "112:169:1"
							},
							{
								"body": {
									"nativeSrc": "349:77:1",
									"nodeType": "YulBlock",
									"src": "349:77:1",
									"statements": [
										{
											"expression": {
												"arguments": [
													{
														"name": "dst",
														"nativeSrc": "366:3:1",
														"nodeType": "YulIdentifier",
														"src": "366:3:1"
													},
													{
														"name": "src",
														"nativeSrc": "371:3:1",
														"nodeType": "YulIdentifier",
														"src": "371:3:1"
													},
													{
														"name": "length",
														"nativeSrc": "376:6:1",
														"nodeType": "YulIdentifier",
														"src": "376:6:1"
													}
												],
												"functionName": {
													"name": "mcopy",
													"nativeSrc": "360:5:1",
													"nodeType": "YulIdentifier",
													"src": "360:5:1"
												},
												"nativeSrc": "360:23:1",
												"nodeType": "YulFunctionCall",
												"src": "360:23:1"
											},
											"nativeSrc": "360:23:1",
											"nodeType": "YulExpressionStatement",
											"src": "360:23:1"
										},
										{
											"expression": {
												"arguments": [
													{
														"arguments": [
															{
																"name": "dst",
																"nativeSrc": "403:3:1",
																"nodeType": "YulIdentifier",
																"src": "403:3:1"
															},
															{
																"name": "length",
																"nativeSrc": "408:6:1",
																"nodeType": "YulIdentifier",
																"src": "408:6:1"
															}
														],
														"functionName": {
															"name": "add",
															"nativeSrc": "399:3:1",
															"nodeType": "YulIdentifier",
															"src": "399:3:1"
														},
														"nativeSrc": "399:16:1",
														"nodeType": "YulFunctionCall",
														"src": "399:16:1"
													},
													{
														"kind": "number",
														"nativeSrc": "417:1:1",
														"nodeType": "YulLiteral",
														"src": "417:1:1",
														"type": "",
														"value": "0"
													}
												],
												"functionName": {
													"name": "mstore",
													"nativeSrc": "392:6:1",
													"nodeType": "YulIdentifier",
													"src": "392:6:1"
												},
												"nativeSrc": "392:27:1",
												"nodeType": "YulFunctionCall",
												"src": "392:27:1"
											},
											"nativeSrc": "392:27:1",
											"nodeType": "YulExpressionStatement",
											"src": "392:27:1"
										}
									]
								},
								"name": "copy_memory_to_memory_with_cleanup",
								"nativeSrc": "287:139:1",
								"nodeType": "YulFunctionDefinition",
								"parameters": [
									{
										"name": "src",
										"nativeSrc": "331:3:1",
										"nodeType": "YulTypedName",
										"src": "331:3:1",
										"type": ""
									},
									{
										"name": "dst",
										"nativeSrc": "336:3:1",
										"nodeType": "YulTypedName",
										"src": "336:3:1",
										"type": ""
									},
									{
										"name": "length",
										"nativeSrc": "341:6:1",
										"nodeType": "YulTypedName",
										"src": "341:6:1",
										"type": ""
									}
								],
								"src": "287:139:1"
							},
							{
								"body": {
									"nativeSrc": "480:54:1",
									"nodeType": "YulBlock",
									"src": "480:54:1",
									"statements": [
										{
											"nativeSrc": "490:38:1",
											"nodeType": "YulAssignment",
											"src": "490:38:1",
											"value": {
												"arguments": [
													{
														"arguments": [
															{
																"name": "value",
																"nativeSrc": "508:5:1",
																"nodeType": "YulIdentifier",
																"src": "508:5:1"
															},
															{
																"kind": "number",
																"nativeSrc": "515:2:1",
																"nodeType": "YulLiteral",
																"src": "515:2:1",
																"type": "",
																"value": "31"
															}
														],
														"functionName": {
															"name": "add",
															"nativeSrc": "504:3:1",
															"nodeType": "YulIdentifier",
															"src": "504:3:1"
														},
														"nativeSrc": "504:14:1",
														"nodeType": "YulFunctionCall",
														"src": "504:14:1"
													},
													{
														"arguments": [
															{
																"kind": "number",
																"nativeSrc": "524:2:1",
																"nodeType": "YulLiteral",
																"src": "524:2:1",
																"type": "",
																"value": "31"
															}
														],
														"functionName": {
															"name": "not",
															"nativeSrc": "520:3:1",
															"nodeType": "YulIdentifier",
															"src": "520:3:1"
														},
														"nativeSrc": "520:7:1",
														"nodeType": "YulFunctionCall",
														"src": "520:7:1"
													}
												],
												"functionName": {
													"name": "and",
													"nativeSrc": "500:3:1",
													"nodeType": "YulIdentifier",
													"src": "500:3:1"
												},
												"nativeSrc": "500:28:1",
												"nodeType": "YulFunctionCall",
												"src": "500:28:1"
											},
											"variableNames": [
												{
													"name": "result",
													"nativeSrc": "490:6:1",
													"nodeType": "YulIdentifier",
													"src": "490:6:1"
												}
											]
										}
									]
								},
								"name": "round_up_to_mul_of_32",
								"nativeSrc": "432:102:1",
								"nodeType": "YulFunctionDefinition",
								"parameters": [
									{
										"name": "value",
										"nativeSrc": "463:5:1",
										"nodeType": "YulTypedName",
										"src": "463:5:1",
										"type": ""
									}
								],
								"returnVariables": [
									{
										"name": "result",
										"nativeSrc": "473:6:1",
										"nodeType": "YulTypedName",
										"src": "473:6:1",
										"type": ""
									}
								],
								"src": "432:102:1"
							},
							{
								"body": {
									"nativeSrc": "632:285:1",
									"nodeType": "YulBlock",
									"src": "632:285:1",
									"statements": [
										{
											"nativeSrc": "642:53:1",
											"nodeType": "YulVariableDeclaration",
											"src": "642:53:1",
											"value": {
												"arguments": [
													{
														"name": "value",
														"nativeSrc": "689:5:1",
														"nodeType": "YulIdentifier",
														"src": "689:5:1"
													}
												],
												"functionName": {
													"name": "array_length_t_string_memory_ptr",
													"nativeSrc": "656:32:1",
													"nodeType": "YulIdentifier",
													"src": "656:32:1"
												},
												"nativeSrc": "656:39:1",
												"nodeType": "YulFunctionCall",
												"src": "656:39:1"
											},
											"variables": [
												{
													"name": "length",
													"nativeSrc": "646:6:1",
													"nodeType": "YulTypedName",
													"src": "646:6:1",
													"type": ""
												}
											]
										},
										{
											"nativeSrc": "704:78:1",
											"nodeType": "YulAssignment",
											"src": "704:78:1",
											"value": {
												"arguments": [
													{
														"name": "pos",
														"nativeSrc": "770:3:1",
														"nodeType": "YulIdentifier",
														"src": "770:3:1"
													},
													{
														"name": "length",
														"nativeSrc": "775:6:1",
														"nodeType": "YulIdentifier",
														"src": "775:6:1"
													}
												],
												"functionName": {
													"name": "array_storeLengthForEncoding_t_string_memory_ptr_fromStack",
													"nativeSrc": "711:58:1",
													"nodeType": "YulIdentifier",
													"src": "711:58:1"
												},
												"nativeSrc": "711:71:1",
												"nodeType": "YulFunctionCall",
												"src": "711:71:1"
											},
											"variableNames": [
												{
													"name": "pos",
													"nativeSrc": "704:3:1",
													"nodeType": "YulIdentifier",
													"src": "704:3:1"
												}
											]
										},
										{
											"expression": {
												"arguments": [
													{
														"arguments": [
															{
																"name": "value",
																"nativeSrc": "830:5:1",
																"nodeType": "YulIdentifier",
																"src": "830:5:1"
															},
															{
																"kind": "number",
																"nativeSrc": "837:4:1",
																"nodeType": "YulLiteral",
																"src": "837:4:1",
																"type": "",
																"value": "0x20"
															}
														],
														"functionName": {
															"name": "add",
															"nativeSrc": "826:3:1",
															"nodeType": "YulIdentifier",
															"src": "826:3:1"
														},
														"nativeSrc": "826:16:1",
														"nodeType": "YulFunctionCall",
														"src": "826:16:1"
													},
													{
														"name": "pos",
														"nativeSrc": "844:3:1",
														"nodeType": "YulIdentifier",
														"src": "844:3:1"
													},
													{
														"name": "length",
														"nativeSrc": "849:6:1",
														"nodeType": "YulIdentifier",
														"src": "849:6:1"
													}
												],
												"functionName": {
													"name": "copy_memory_to_memory_with_cleanup",
													"nativeSrc": "791:34:1",
													"nodeType": "YulIdentifier",
													"src": "791:34:1"
												},
												"nativeSrc": "791:65:1",
												"nodeType": "YulFunctionCall",
												"src": "791:65:1"
											},
											"nativeSrc": "791:65:1",
											"nodeType": "YulExpressionStatement",
											"src": "791:65:1"
										},
										{
											"nativeSrc": "865:46:1",
											"nodeType": "YulAssignment",
											"src": "865:46:1",
											"value": {
												"arguments": [
													{
														"name": "pos",
														"nativeSrc": "876:3:1",
														"nodeType": "YulIdentifier",
														"src": "876:3:1"
													},
													{
														"arguments": [
															{
																"name": "length",
																"nativeSrc": "903:6:1",
																"nodeType": "YulIdentifier",
																"src": "903:6:1"
															}
														],
														"functionName": {
															"name": "round_up_to_mul_of_32",
															"nativeSrc": "881:21:1",
															"nodeType": "YulIdentifier",
															"src": "881:21:1"
														},
														"nativeSrc": "881:29:1",
														"nodeType": "YulFunctionCall",
														"src": "881:29:1"
													}
												],
												"functionName": {
													"name": "add",
													"nativeSrc": "872:3:1",
													"nodeType": "YulIdentifier",
													"src": "872:3:1"
												},
												"nativeSrc": "872:39:1",
												"nodeType": "YulFunctionCall",
												"src": "872:39:1"
											},
											"variableNames": [
												{
													"name": "end",
													"nativeSrc": "865:3:1",
													"nodeType": "YulIdentifier",
													"src": "865:3:1"
												}
											]
										}
									]
								},
								"name": "abi_encode_t_string_memory_ptr_to_t_string_memory_ptr_fromStack",
								"nativeSrc": "540:377:1",
								"nodeType": "YulFunctionDefinition",
								"parameters": [
									{
										"name": "value",
										"nativeSrc": "613:5:1",
										"nodeType": "YulTypedName",
										"src": "613:5:1",
										"type": ""
									},
									{
										"name": "pos",
										"nativeSrc": "620:3:1",
										"nodeType": "YulTypedName",
										"src": "620:3:1",
										"type": ""
									}
								],
								"returnVariables": [
									{
										"name": "end",
										"nativeSrc": "628:3:1",
										"nodeType": "YulTypedName",
										"src": "628:3:1",
										"type": ""
									}
								],
								"src": "540:377:1"
							},
							{
								"body": {
									"nativeSrc": "1041:195:1",
									"nodeType": "YulBlock",
									"src": "1041:195:1",
									"statements": [
										{
											"nativeSrc": "1051:26:1",
											"nodeType": "YulAssignment",
											"src": "1051:26:1",
											"value": {
												"arguments": [
													{
														"name": "headStart",
														"nativeSrc": "1063:9:1",
														"nodeType": "YulIdentifier",
														"src": "1063:9:1"
													},
													{
														"kind": "number",
														"nativeSrc": "1074:2:1",
														"nodeType": "YulLiteral",
														"src": "1074:2:1",
														"type": "",
														"value": "32"
													}
												],
												"functionName": {
													"name": "add",
													"nativeSrc": "1059:3:1",
													"nodeType": "YulIdentifier",
													"src": "1059:3:1"
												},
												"nativeSrc": "1059:18:1",
												"nodeType": "YulFunctionCall",
												"src": "1059:18:1"
											},
											"variableNames": [
												{
													"name": "tail",
													"nativeSrc": "1051:4:1",
													"nodeType": "YulIdentifier",
													"src": "1051:4:1"
												}
											]
										},
										{
											"expression": {
												"arguments": [
													{
														"arguments": [
															{
																"name": "headStart",
																"nativeSrc": "1098:9:1",
																"nodeType": "YulIdentifier",
																"src": "1098:9:1"
															},
															{
																"kind": "number",
																"nativeSrc": "1109:1:1",
																"nodeType": "YulLiteral",
																"src": "1109:1:1",
																"type": "",
																"value": "0"
															}
														],
														"functionName": {
															"name": "add",
															"nativeSrc": "1094:3:1",
															"nodeType": "YulIdentifier",
															"src": "1094:3:1"
														},
														"nativeSrc": "1094:17:1",
														"nodeType": "YulFunctionCall",
														"src": "1094:17:1"
													},
													{
														"arguments": [
															{
																"name": "tail",
																"nativeSrc": "1117:4:1",
																"nodeType": "YulIdentifier",
																"src": "1117:4:1"
															},
															{
																"name": "headStart",
																"nativeSrc": "1123:9:1",
																"nodeType": "YulIdentifier",
																"src": "1123:9:1"
															}
														],
														"functionName": {
															"name": "sub",
															"nativeSrc": "1113:3:1",
															"nodeType": "YulIdentifier",
															"src": "1113:3:1"
														},
														"nativeSrc": "1113:20:1",
														"nodeType": "YulFunctionCall",
														"src": "1113:20:1"
													}
												],
												"functionName": {
													"name": "mstore",
													"nativeSrc": "1087:6:1",
													"nodeType": "YulIdentifier",
													"src": "1087:6:1"
												},
												"nativeSrc": "1087:47:1",
												"nodeType": "YulFunctionCall",
												"src": "1087:47:1"
											},
											"nativeSrc": "1087:47:1",
											"nodeType": "YulExpressionStatement",
											"src": "1087:47:1"
										},
										{
											"nativeSrc": "1143:86:1",
											"nodeType": "YulAssignment",
											"src": "1143:86:1",
											"value": {
												"arguments": [
													{
														"name": "value0",
														"nativeSrc": "1215:6:1",
														"nodeType": "YulIdentifier",
														"src": "1215:6:1"
													},
													{
														"name": "tail",
														"nativeSrc": "1224:4:1",
														"nodeType": "YulIdentifier",
														"src": "1224:4:1"
													}
												],
												"functionName": {
													"name": "abi_encode_t_string_memory_ptr_to_t_string_memory_ptr_fromStack",
													"nativeSrc": "1151:63:1",
													"nodeType": "YulIdentifier",
													"src": "1151:63:1"
												},
												"nativeSrc": "1151:78:1",
												"nodeType": "YulFunctionCall",
												"src": "1151:78:1"
											},
											"variableNames": [
												{
													"name": "tail",
													"nativeSrc": "1143:4:1",
													"nodeType": "YulIdentifier",
													"src": "1143:4:1"
												}
											]
										}
									]
								},
								"name": "abi_encode_tuple_t_string_memory_ptr__to_t_string_memory_ptr__fromStack_reversed",
								"nativeSrc": "923:313:1",
								"nodeType": "YulFunctionDefinition",
								"parameters": [
									{
										"name": "headStart",
										"nativeSrc": "1013:9:1",
										"nodeType": "YulTypedName",
										"src": "1013:9:1",
										"type": ""
									},
									{
										"name": "value0",
										"nativeSrc": "1025:6:1",
										"nodeType": "YulTypedName",
										"src": "1025:6:1",
										"type": ""
									}
								],
								"returnVariables": [
									{
										"name": "tail",
										"nativeSrc": "1036:4:1",
										"nodeType": "YulTypedName",
										"src": "1036:4:1",
										"type": ""
									}
								],
								"src": "923:313:1"
							}
						]
					},
					"contents": "{\n\n    function array_length_t_string_memory_ptr(value) -> length {\n\n        length := mload(value)\n\n    }\n\n    function array_storeLengthForEncoding_t_string_memory_ptr_fromStack(pos, length) -> updated_pos {\n        mstore(pos, length)\n        updated_pos := add(pos, 0x20)\n    }\n\n    function copy_memory_to_memory_with_cleanup(src, dst, length) {\n\n        mcopy(dst, src, length)\n        mstore(add(dst, length), 0)\n\n    }\n\n    function round_up_to_mul_of_32(value) -> result {\n        result := and(add(value, 31), not(31))\n    }\n\n    function abi_encode_t_string_memory_ptr_to_t_string_memory_ptr_fromStack(value, pos) -> end {\n        let length := array_length_t_string_memory_ptr(value)\n        pos := array_storeLengthForEncoding_t_string_memory_ptr_fromStack(pos, length)\n        copy_memory_to_memory_with_cleanup(add(value, 0x20), pos, length)\n        end := add(pos, round_up_to_mul_of_32(length))\n    }\n\n    function abi_encode_tuple_t_string_memory_ptr__to_t_string_memory_ptr__fromStack_reversed(headStart , value0) -> tail {\n        tail := add(headStart, 32)\n\n        mstore(add(headStart, 0), sub(tail, headStart))\n        tail := abi_encode_t_string_memory_ptr_to_t_string_memory_ptr_fromStack(value0,  tail)\n\n    }\n\n}\n",
					"id": 1,
					"language": "Yul",
					"name": "#utility.yul"
				}
			],
			"immutableReferences": {},
			"linkReferences": {},
			"object": "608060405234801561000f575f80fd5b5060043610610029575f3560e01c806313bdfacd1461002d575b5f80fd5b61003561004b565b60405161004291906100f8565b60405180910390f35b60606040518060400160405280600c81526020017f48656c6c6f20576f726c64210000000000000000000000000000000000000000815250905090565b5f81519050919050565b5f82825260208201905092915050565b8281835e5f83830152505050565b5f601f19601f8301169050919050565b5f6100ca82610088565b6100d48185610092565b93506100e48185602086016100a2565b6100ed816100b0565b840191505092915050565b5f6020820190508181035f83015261011081846100c0565b90509291505056fea2646970667358221220f547b39c1ac7ab00ddd4bcf1b194a40ea7069ecae4ebc5a680097b5072ac06d864736f6c63430008190033",
			"opcodes": "PUSH1 0x80 PUSH1 0x40 MSTORE CALLVALUE DUP1 ISZERO PUSH2 0xF JUMPI PUSH0 DUP1 REVERT JUMPDEST POP PUSH1 0x4 CALLDATASIZE LT PUSH2 0x29 JUMPI PUSH0 CALLDATALOAD PUSH1 0xE0 SHR DUP1 PUSH4 0x13BDFACD EQ PUSH2 0x2D JUMPI JUMPDEST PUSH0 DUP1 REVERT JUMPDEST PUSH2 0x35 PUSH2 0x4B JUMP JUMPDEST PUSH1 0x40 MLOAD PUSH2 0x42 SWAP2 SWAP1 PUSH2 0xF8 JUMP JUMPDEST PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST PUSH1 0x60 PUSH1 0x40 MLOAD DUP1 PUSH1 0x40 ADD PUSH1 0x40 MSTORE DUP1 PUSH1 0xC DUP2 MSTORE PUSH1 0x20 ADD PUSH32 0x48656C6C6F20576F726C64210000000000000000000000000000000000000000 DUP2 MSTORE POP SWAP1 POP SWAP1 JUMP JUMPDEST PUSH0 DUP2 MLOAD SWAP1 POP SWAP2 SWAP1 POP JUMP JUMPDEST PUSH0 DUP3 DUP3 MSTORE PUSH1 0x20 DUP3 ADD SWAP1 POP SWAP3 SWAP2 POP POP JUMP JUMPDEST DUP3 DUP2 DUP4 MCOPY PUSH0 DUP4 DUP4 ADD MSTORE POP POP POP JUMP JUMPDEST PUSH0 PUSH1 0x1F NOT PUSH1 0x1F DUP4 ADD AND SWAP1 POP SWAP2 SWAP1 POP JUMP JUMPDEST PUSH0 PUSH2 0xCA DUP3 PUSH2 0x88 JUMP JUMPDEST PUSH2 0xD4 DUP2 DUP6 PUSH2 0x92 JUMP JUMPDEST SWAP4 POP PUSH2 0xE4 DUP2 DUP6 PUSH1 0x20 DUP7 ADD PUSH2 0xA2 JUMP JUMPDEST PUSH2 0xED DUP2 PUSH2 0xB0 JUMP JUMPDEST DUP5 ADD SWAP2 POP POP SWAP3 SWAP2 POP POP JUMP JUMPDEST PUSH0 PUSH1 0x20 DUP3 ADD SWAP1 POP DUP2 DUP2 SUB PUSH0 DUP4 ADD MSTORE PUSH2 0x110 DUP2 DUP5 PUSH2 0xC0 JUMP JUMPDEST SWAP1 POP SWAP3 SWAP2 POP POP JUMP INVALID LOG2 PUSH5 0x6970667358 0x22 SLT KECCAK256 CREATE2 SELFBALANCE 0xB3 SWAP13 BYTE 0xC7 0xAB STOP 0xDD 0xD4 0xBC CALL 0xB1 SWAP5 LOG4 0xE 0xA7 MOD SWAP15 0xCA 0xE4 0xEB 0xC5 0xA6 DUP1 MULMOD PUSH28 0x5072AC06D864736F6C63430008190033000000000000000000000000 ",
			"sourceMap": "66:159:0:-:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;138:85;;;:::i;:::-;;;;;;;:::i;:::-;;;;;;;;;176:13;197:21;;;;;;;;;;;;;;;;;;;138:85;:::o;7:99:1:-;59:6;93:5;87:12;77:22;;7:99;;;:::o;112:169::-;196:11;230:6;225:3;218:19;270:4;265:3;261:14;246:29;;112:169;;;;:::o;287:139::-;376:6;371:3;366;360:23;417:1;408:6;403:3;399:16;392:27;287:139;;;:::o;432:102::-;473:6;524:2;520:7;515:2;508:5;504:14;500:28;490:38;;432:102;;;:::o;540:377::-;628:3;656:39;689:5;656:39;:::i;:::-;711:71;775:6;770:3;711:71;:::i;:::-;704:78;;791:65;849:6;844:3;837:4;830:5;826:16;791:65;:::i;:::-;881:29;903:6;881:29;:::i;:::-;876:3;872:39;865:46;;632:285;540:377;;;;:::o;923:313::-;1036:4;1074:2;1063:9;1059:18;1051:26;;1123:9;1117:4;1113:20;1109:1;1098:9;1094:17;1087:47;1151:78;1224:4;1215:6;1151:78;:::i;:::-;1143:86;;923:313;;;;:::o"
		},
		"gasEstimates": {
			"creation": {
				"codeDepositCost": "66800",
				"executionCost": "115",
				"totalCost": "66915"
			},
			"external": {
				"print()": "infinite"
			}
		},
		"methodIdentifiers": {
			"print()": "13bdfacd"
		}
	},
	"abi": [
		{
			"inputs": [],
			"name": "print",
			"outputs": [
				{
					"internalType": "string",
					"name": "",
					"type": "string"
				}
			],
			"stateMutability": "pure",
			"type": "function"
		}
	]
}
