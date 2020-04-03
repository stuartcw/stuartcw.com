---
layout: "post"
title: "What I learned this month - April 2020"
date: "2020-04-01 13:49"
---
# What I learned in April 2020

## Python

# DeepDiff to find out what changed between data structures. 

```
from deepdiff import DeepDiff

def compareLists(l1,l2,sortby=None):
	l1.sort(key=sortby)
	l2.sort(key=sortby)
	
	changes=DeepDiff(l1,l2,ignore_order=True)
	print(changes)
	
	if 'iterable_item_added' in changes: 
		addedItems=changes['iterable_item_added']
		for addition in addedItems:
			print("New:",addedItems[addition])
		
	if 	'iterable_item_removed' in changes:
		missingItems=changes['iterable_item_removed']
		for missing in missingItems:
			print("Missing:",missingItems[missing])
	
l1=[10,20,30,40]
l2=[10,20,30,40,50]

compareLists(l1, l2 )
```



## Shell

### ShellCheck

Finds bugs in your shell scripts.

* [ShellCheck](https://github.com/koalaman/shellcheck)

## To Learn

* How to write a simple slack bot on PythoAnywhere
* Find out how to use a different template on GitHub Pages.
* Slack API 
