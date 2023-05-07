Download Link: https://assignmentchef.com/product/solved-palindrome-c
<br>
Write a program that uses a stack object to determine if a string is a palindrome (i.e. the string is spelled identically backward and forward). The program should ignore spaces and punctuation.

Go ahead and start your program by reading in a C-style string from standard input, using the getline function. You may assume a limit of 100 characters on the string (although this can be written, with a little more effort, to accept any size string). Your algorithm must make use of a stack (of type char). Use the Deitel implementation of the Stack from “stack.h” (you <strong>don’t</strong> need to change this file).

Ignore spacing and punctuation, as well as special characters and digits (i.e. only count letters as part of a palindrome, and account for upper/lower case. For example, ‘B’ and ‘b’ are matching letters).

<strong>Sample runs</strong>: (user input underlined)

<pre class="ql-syntax">  Please enter a <span class="hljs-keyword">string</span>:  &gt; ABCDEFGHGFEDCBA  <span class="hljs-string">"ABCDEFGHGFEDCBA"</span>  IS a palindrome  Please enter a <span class="hljs-keyword">string</span>:  &gt; The quick brown fox  <span class="hljs-string">"The quick brown fox"</span>  <span class="hljs-keyword">is</span> NOT palindrome  Please enter a <span class="hljs-keyword">string</span>:  &gt; Cigar? Toss it <span class="hljs-keyword">in</span> a can. It <span class="hljs-keyword">is</span> so tragic.  <span class="hljs-string">"Cigar? Toss it in a can. It is so tragic."</span>  IS a palindrome</pre>