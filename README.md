Simply Is
====================
An expressive type testing utility library for Node.

[GITHUB:	https://github.com/anonmily/simply-is](https://github.com/anonmily/simply-is)

[NPM:		https://www.npmjs.com/package/simply-is](https://www.npmjs.com/package/simply-is)

## Install
    npm install simply-is

## Examples
	is.object({}); 			//true
	is.a.string('hello')	//chaining
	is.not.an.array({})		//negation
	is(3).even()			//alternative syntax

## Basic Tests
	is.object 		({})
	is.array 		([1,2,3])
	is.string 		('hello world')
	is.json 		('[{"key":"somevalue"}]')
	is.number 		(1)
	is.null 		(Null)
	is.undefined 	(undefined)
	is.boolean 		(1==1)

## Utility
	is.empty		({}) //true for {}, [], 0, "", null, undefined

## Numbers
	is.number		(1)
	is.nan			(NaN)
	is.infinite		(Infinity)
	is.even			(2)
	is.odd			(3)

## Booleans
	is.boolean  	(true)
	is.true			(1==1)
	is.false		(1==2)
