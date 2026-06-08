# react-bem-classes

- Better package name?
- Refactor to be non-nested
- Look into nested usage - are there problems?
- More robust block detection!
  - Interoperability with classnames (order independent?)
- Functional classes
- Potential new interface(?):

```ts
import reactBem from 'react-bem';

class Component() {
  const name = 'Anna', age = 42;
  return reactBem(<section className="User:& &-active">
    <ul className="&_details">
      <li className="&_name">
        Name: <span className="&_name &-highlight">{name}</span>
      </li>
      <li className="&_age italic">Age: {age}</li>
    </ul>
  </section>);
}
```
