## Scratch 
David Mayland is the Professor for Harvard Cs50x 

"Computational thinking"- how to think through problems via differnt logic paths to come to an outcome

When we have "Input" this is the problem we are wanting to solve.

We then would have input -> [process] -> output

Unarity notation -- Base 1-- in math is just counting with your fingers
Base-2 - binary system

- Binary digit - also known as a bit == Bi+T (Bi-nary + t-digi) 
-  0 light off \ 1 Light on

If we look at this in computers, we have transistors which can be thought of simply as little lights in a computer, different combos of off and on would mean we get different effects

Basic Bit example 
000=0
100=1
010=2
110=3
001=4
101=5
110=6
111=7 (8-bit? Or a Byte!)(This I think would be more of what 8 bit is as 0 counts as an option)
1000=8 Adding a new column means you are adding more memory to the computer 

100010110= 123 

# Backing up and looking at how humans learn numbers
It is also representing the hundreds column, the 10s columna and the 1s column

100's 10's 1's
10^2 10^1 10^0

10^2*2.31= 100*2.31= 231?

But if we only have a 2 base rather than a 10 base. 

2^2 2^1 2^0
4 2 1 (?) Come back to this 

If we have 8 bytes
2^7 2^6 2^5 2^4 2^3 2^2 2^1 2^0
128 64 32 16 8 4 2 1

2^7= 128 
2^6= 64
2^5= 32
2^4= 16
2^3=8
2^2=4
2^1=2
2^0=1

The math
128 64 32 16 8 4 2 1 
00000000 

So if we decided we wanted to know how high we could count with this it would be what we had above just added together +1 which would represent the 0 state 
1+128+64+32+16+8+4+2+1=256

= How high can you count with this then? 256 

To summarize: 
Traditional binary computer can count in 0's or 1's. On or offs. If we transpose how we look at numbers into 10's we would get 100's 10's and 1's then give it a power (10^2 = 100 for example) you see how we counting in 10's get a number. If we apply that to a binary system 2^2 for example you 4. which would mean you only have 3 bits (which means you can count to 4). You can always count how high your system can count / 32gb (you'd be able to see how high it could count. 

This is implies bigger is better... but thats not true... All it is saying is the fact that it can only count so high. There feels like an implecation that bigger is better (maybe). It just means that is all it can count, we need to see and think through how ai models are processed through bits / bytes and how that translates to Vram

There are tunary computers that use 0,1,and 2!

# Part 2
- Now what how do we represent letters? CS folks deicded the solution was to just decide we are going to go with setting 01000001=A. 
- If we look again at our binary
128 64 32 16 8 4 2 1
01000001 If we count up the positions you get A as 65, (position 64+1). They then go up from there of 66=B
Which would be 01000010, C would then be 01000011 as that equals 67

- Lower case letters are 97, 98 etc.

- So what is the system that we just talked to above? ASCII- is the mapping system "American Standard Code for Infomation Interchange"

- 

 As a binary counting system 


