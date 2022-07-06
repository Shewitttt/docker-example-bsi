# Heading 1

-Function purpose- calculate the premium for healthcare workers
-Do the test case with for loop
-user can insert negative number
-user can insert 0
-first wrote tests
-strategy--to write functions

for(let i = 0;i <= 10; i++){
it('Should multiply by \*1.2 when s/he has less than 10 year experience', () => {
expect((solution({profession: 'nurse', experience: i}, 200))).toBe(240)
});
}
