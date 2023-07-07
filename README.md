- https://github.com/honkit/honkit/issues/354

# TEST

```javascript
person.toString = function () {
  return "I'm " + this.age;
};
```

## BUILD

    npm run build