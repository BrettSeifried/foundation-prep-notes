Calul test

```// IMPORT MODULES under test here:
// import { example } from '../example.js';

const test = QUnit.test;

function add_two(num){
    return num + 2;
}

test('time add_two function', (expect) => {
    //Arrange
    // Set up your arguments and expectations
    const expected = 4;
    
    //Act 
    // Call the function you're testing and set the result to a const
    const actual = add_two(2);

    //Expect
    // Make assertions about what is expected versus the actual result
    expect.equal(actual, expected);
});
```