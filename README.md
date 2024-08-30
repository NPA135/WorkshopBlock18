# [ Psuedo for function multiplication() ] - Unit Test
- Multiply two numbers together.
- Accept two numbers as an argument.
- Return a single number.
- Return the product of two input numbers.

Examples:
- expect.multiplication(2,3).toBe(6)
- expect.multiplication(15,2).toBe(30)
- expect.multiplication(7,7).toBe(49)

------------------------------------------------------

## [ Pseudo for function concatOdds() ] - Unit Test
- Takes two arrays of integers as arguments.
- Should return a single array that only contains the odd numbers.
- Should return the odd numbers in ascending order from both arrays.

Examples:
- expect.concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]).toBe([-1, 1, 3, 9, 15])
- expect.concatOdds([2, 1], [9, 4, 15, -1]).toBe([-1, 9, 15])
- expect.concatOdds([3, 2, 1], [1, 1, 1, 4, -1]).toBe([-1, 1, 3])

- Only one argument is given instead of two.
- Arguments of different types (strings, objects, etc.,) are given.
- No arguments are given.
- More than two arguments are given.

### [ Shopping Cart ] - Functional Test

What should happen if the cart is empty?
- Tell users their cart is empty.
- Provide a redirect link back to shopping items.

What needs to be shown to the user at each step of check out?
- Check out button prompt.
- Input payment method.
- Input billing and shipping details.
- Save payment information prompt.
- If an account is not already created after selecting save information, a prompt to have users create an account.
- Confirm order button prompt.
- "Your order has been placed" finishing screen and a return to shop link.

What behaviors of this feature does the prompt miss or gloss over?
- Glosses over options to create new accounts, although the option is provided it is not the priority to the check out.