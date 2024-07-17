# SHA-256_Verilog_Implementaion
SHA-2 (Secure Hash Algorithm 2), which includes SHA-256, is among the most widely used hashing algorithms today. Renowned for its security—unlike SHA-1, which has been compromised—SHA-2 is also noted for its speed. This makes it particularly effective in scenarios where key generation isn't required, such as Bitcoin mining, where a fast hash algorithm like SHA-2 is highly advantageous.

## General Hash Computational Flow
![image](https://github.com/164adityakumar/curly-dollop/assets/98655260/edfc7cbe-8ff4-41ff-a84a-2a83a2bf31c1)

# Working
The SHA-256 compression function op erates on a 512-bit message block and a 256-
bit intermediate hash value. It is essentially a 256-bit blo ck cipher algorithm which
encrypts the intermediate hash value using the message blo ck as key. Hence there
are two main comp onents to describe: (1) the SHA-256 compression function, and
(2) the SHA-256 message schedule.

## Algorithm steps
1. Pre-Processing
2. Initialize Hash Values (h)
3. Initialize Round Constants (k)
4. Chunk Loop
5. Create Message Schedule (w)
6. Compression
7. Modify Final Values
8. Concatenate Final Hash


## Compression Function
![image](https://github.com/164adityakumar/curly-dollop/assets/98655260/6591b2a1-e7e3-4ac7-9263-9b790cc000b0)

## Message Schedule
![image](https://github.com/164adityakumar/curly-dollop/assets/98655260/972c3405-4d83-4064-a3c9-d68c923c796b)



