### C#HW16
## Cox, Cody C.

1. Give ﬁve examples (using valid C# code) of the ﬁve bitwise operators listed in the text.
|, &, ^, <<, >>

2. Does C# implement the right-shift (>>) operator? If so, give an example of its operation using value C# code.
Yes, bits 5 >> index

3. Explain in detail this code: bits & (1 << index);.
1 is shifted by index = result bits & result = 1 if both are true (1 & 1 = 1)

4. Explain in detail this code: bits |= (1 << index);.
1 is shifted by index = result bit at index is evaluated to true regardless of its first state

5. Explain in detail this code: bits &= (1 << index);.
1 is shifted by index = result bits & result = true if both bits and result are true

6. How does C# interpret this? bool peek = bits[n];
This will display 1 or 0 depending on the value at index n

7. How does C# interpret this? bits[n] = true;
Sets the value at index n to true

8. How does C# interpret this? bits[n] ^= true;
Sets the value at index to false

9. Assume that users were assigned read, write, and execute permissions according to this scheme: read = 1, write = 2, execute = 4. How would you interpret the following user permissions:
(a) permission = 0 (b) permission = 1 (c) permission = 2 (d) permission = 3 (e) permission = 4 (f) permission = 5 (g) permission = 6 (h) permission = 7
(a) permission = 0 none (b) permission = 1 read (c) permission = 2 write (d) permission = 3 r + w (e) permission = 4 execute (f) permission = 5 e + r (g) permission = 6 e + w (h) permission = 7 e + w + r

10. Answer the previous question by converting the decimal permissions into binary permissions. What does this tell you about using this scheme of permissions?
00000001, 00000010, 00000100
