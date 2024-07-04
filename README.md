
Transaction Link: https://explorer.solana.com/tx/5jEmiCkXvWj55eFeLF8gA5XCF3cYE715zaEEyES99XkmzsN1uAqqy6fds7imL7wx4CAk6LSzEPpUW3TAt81g4rky?cluster=devnet


What does it do?

1. It creates a new keypair and a connection.
2. It creates a new program from the IDL file.
3. From the IDL file we can see that there are 2 instructions our program can handle: `complete` and `update`
4. We create a transaction sending our github account to the program. The program shall get our github account and *enroll* us. This will confirm we have completed the bootcamp.

To make the transaction you need to run this in the cli: `yarn enroll`