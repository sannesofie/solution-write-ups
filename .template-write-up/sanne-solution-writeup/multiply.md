# Solution write up

## [Multiply]

> this function will myltiply numbers

## Syntax

> multiply(Number) -> Number

### Parameters

**paramName**: number1, number2

- 2 numbers given by the user to multiply the numbers

### Return Value

num1 * num2

## Test Cases

```js

describe('it should return 0', () => {
    it('',  () => {
      const actual = multiply(3, 0);
      const expected = 0;
      expect(actual).toEqual(expected);
    })});

    //when multiplied with negative number always less than 0
describe('it should return less than zero', () => {
    it('',  () => {
        const actual = multiply(3, -6) < 0;
        const expected =  true;
        expect(actual).toEqual(expected);
      })});

// when multiplied with Infinity always NaN
describe('it should return NaN', () => {
    it('',  () => {
      const actual = multiply(Infinity, 0);
      const expected = NaN;
      expect(actual).toEqual(expected);
})});   

// when multiplied with string always NaN
describe('it should return NaN', () => {
  it('',  () => {
    const actual = multiply('hello', 0);
    const expected = NaN;
    expect(actual).toEqual(expected);
  })});
  
 ```

## Use Cases

## Edge Cases

- negative numbers, gives zero
- Infinity, gives NaN

---

## Retrospective

As this is my very first (on my own) write up I have learned a lot from it by
going over my own function

I found great use in MDN Docs.

### Continue Doing

When working on something, keep trying to find the solution it often works

### Start Doing

If feeling a bit lost ask for help

### Stop Doing
