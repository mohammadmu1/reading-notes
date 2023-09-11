- Hashing is like turning your password into a secret code that's impossible to turn back into the original password.

- A hash function is like a secret blender for passwords. It takes your password and turns it into a scrambled code that can't be unscrambled to reveal your password.


- 'salt' a password means to add a secret extra code or random characters to the password before hashing it. This makes the password more secure because even if someone gets the hashed password, they won't know what the original password was without the 'salt.' It's like adding a secret ingredient to a recipe that only you know.

- A hacker would need to access your source code or the place where the 'salt' is stored in order to find the 'salt' string for your passwords.


1. **How Blowfish Handles Computer Speed**: Blowfish, a block cipher used in jBCrypt, can adjust its computation cost. As computers get faster, Blowfish can increase the work it requires to hash passwords. This means it intentionally slows down the process as computers become more powerful, making it harder for hackers to crack passwords quickly.

2. **Issues with Common Java Password Hashes**:
   - **Unsalted Hash**: One common Java password hash doesn't use a 'salt,' which makes it easier for hackers to guess passwords using pre-made lists.
   - **Reversible Encryption**: Another method recommends reversible encryption, which is not secure for storing passwords because it allows passwords to be easily decrypted, posing a security risk.
