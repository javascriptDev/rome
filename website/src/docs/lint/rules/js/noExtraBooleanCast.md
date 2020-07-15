---
title: Lint Rule js/noExtraBooleanCast
layout: layouts/page.njk
description: MISSING DOCUMENTATION
eleventyNavigation: {
	key: lint-rules/js/noExtraBooleanCast,
	parent: lint-rules,
	title: js/noExtraBooleanCast
}
---

# js/noExtraBooleanCast

MISSING DOCUMENTATION

<!-- EVERYTHING BELOW IS AUTOGENERATED. SEE SCRIPTS FOLDER FOR UPDATE SCRIPTS -->


## Examples
## Invalid
```typescript
if (Boolean(foo)) {}
```
```typescript
while (!!foo) {}
```
```typescript
let x = 1;
do {
	1 + 1;
} while (Boolean(x));
```
```typescript
for (; !!foo; ) {}
```
## Valid