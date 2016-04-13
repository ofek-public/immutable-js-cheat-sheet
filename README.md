# Immutable.js Cheat Sheet

### Map
```javascript
    var map = Immutable.Map({ a: 1, b: 2, c: 3 });
    map.set('a', 10).get('a');							// 10
    map.merge({'a': 10, 'b': 20}); 						// { a: 10, b: 20, c: 3 }
```

