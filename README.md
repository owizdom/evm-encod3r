# Reversing the EVM WITH EVM-ENC0D3R

This is a simple project that teaches you how to reverse engineer data in the EVM using the encode and decode function

### Encoding and Decoding data

- **Encoding**: Types are passed into `abi.encode(parameters)` to generate the raw calldata. For a specific function, `abi.encodeWithSelector(selector, parameters)` encodes calldata for a specific interfaced function.
- **Decoding**: If you made calldata with `abi.encode(...)`, you can read it with `abi.decode(...)`. For example: `(uint256 a, uint256 b) = abi.decode(data, (uint256, uint256));`

### Conclusion

That's the end of the project as it goes over encoding and decoding uint256 and strings on the EVM
feel free to fork and practice with the project

Fun fact: It was developed on Remix

### Credits/Resources used in creating this:

[reverse-evm-calldata-poc](https://github.com/Otaiki1/reverse-evm-calldata-poc)

[abi-encode-and-decode-using-solidity](https://medium.com/coinmonks/abi-encode-and-decode-using-solidity-2d372a03e110)
