## Tests

### Describe: isLeapYear()
Test: "It returns false for years that are not a leap year"
Expect(isLeapYear(1993)).toEqual(false);

Test: "It returns true for years that are divisible by 4"
Expect(isLeapYear(2004)).toEqual(true);

Test: "It returns false for years that are divisible by 100"
Expect(isLeapYear(2100)).toEqual(false);

Test: "It returns true for years that are divisible by 400"
Expect(isLeapYear(2000)).toEqual(true);
