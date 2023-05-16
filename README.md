# TDD Sample

## Test-Driven Development

### Cover
- Basic of TDD
- using TDD to write business logic
- Refactoring

#### Basics of Test-Driven Development

When we use TDD we start to write tests before we start our implementation.
We start writing a failing test, the test describes what the code will do but if fails because it misses the implementation.
After the first phase, we write the necessary code to make the test pass successfully.

Failing test(RED)  ---write necessary code --> Successfully test(Green)

                <----(Refactor(Clean and optimize code)--->
                
After making the test pass we start the refactoring process. And we iterate from Red to Green during the refactoring process.

#### Using TDD to write business logic

Requirements:
1. Response should contain the same values as the request after booking.
2. Booking should be saved to the database.

#### Refactoring
Clean code
SOLID
DRY
