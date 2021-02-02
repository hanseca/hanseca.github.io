---
layout: project
type: project
image: images/sha-1 final.png
title: SHA-1 Algorithm
permalink: projects/SHA-1
# All dates must be YYYY-MM-DD format!
date: 2019-05-06
labels:
  - Encryption
  - Algorithms
  - C++
summary: Developed an encryption algorithm as a final project for ICS 212.
---
  <img class="ui image" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Cryptographic_Hash_Function.svg/375px-Cryptographic_Hash_Function.svg.png">

The final project for ICS 212 was to develop an encryption algorithm based on SHA-1 documentations and test it on files with random messages in them. It would essentially take a file and run the encryption algorithm and output a message digest in a separate text file. The language used to develop this project in C++.

This final project was done on your own, but was given half a semester to work on it. When the project was given, you needed to read the documentation given for the project on how SHA-1 was done, and use either C or C++ to develop it. Some of the key things for the algorithm to be successful was properly making the bit shift operations do what they are supposed to do to encrypt the file, making sure it can properly read the file and output the message digest correctly, and compressing the characters as an int from the file into a message array. 

The process of working on the project itself in a way was a breeze for the most part. Its development was the culmination of all the C++ assignments done throughout the second half of the semester, and referring to those assignments, I was able to create the core of the algorithm without major problems. I feel that referring to previous C++ assignments while developing the algorithm is something important to do to help give ideas on how something should be made. This project put my understanding of C++ so far to the test and checked my debugging abilities for when the message digest was not outputting correctly.

Source: <a href="https://github.com/hanseca/ICS-212-Final-Project"><i class="large github icon"></i>SHA-1</a>
