# Primevalis

<p align="center">
  <img src="docs/images/logo.png" alt="HTML Linter Logo" width="200">
</p>

## Overview

This library provides a function to determine whether a given number between 1 and 1000 is prime. The `is_prime` function evaluates the primality of a number by checking predefined conditions for each number in the specified range.

Currently, this library supports numbers between 1 and 1000, but future versions may extend support to a broader range.

## Function Usage

```rust
use primevalis::is_prime;

// Check if 17 is prime
let result = is_prime(17);  // returns true

// Check if 24 is prime
let result = is_prime(24);  // returns false
```

### Parameters

- `n` (i32): The integer to check for primality. This function only handles numbers between 1 and 1000.

### Return Value

- `bool`: Returns `true` if the number `n` is prime, `false` otherwise.

## Limitations

- This library currently only supports numbers in the range from 1 to 1000. Future versions may extend this range to accommodate larger numbers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

We welcome contributions to improve this library. If you have an idea or bug fix, please feel free to fork the repository, create a branch, and submit a pull request. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new pull request.

Please ensure that your changes are well-documented and include tests where applicable.

## Future Plans

In future releases, the scope of the library may be extended to support prime number testing for larger ranges, improved algorithms, and additional optimizations.

## Acknowledgments

This library was inspired by simple and educational approaches to prime number checking. Thank you to the Rust community for providing excellent resources and support for open-source development.
