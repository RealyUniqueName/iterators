# Iterators

This is a set of frequently used iterators for Haxe collections and other types.

All iterators are designed to have zero impact on runtime performance.

# Installation

```
haxelib install iterators
```

# Usage

```haxe
using Iterators;

for(i in 10.to(0).step(-2)) {
	trace(i);
}

var map = ['hello' => 'world'];
for(p in map.pairs()) {
	trace(p.key);
	trace(p.value);
}

var str = 'hello';
for(c in str.chars()) {
	trace(c);
}
```

See [Iterators.hx](https://github.com/RealyUniqueName/Iterators/blob/master/src/Iterators.hx) for all available extensions.


