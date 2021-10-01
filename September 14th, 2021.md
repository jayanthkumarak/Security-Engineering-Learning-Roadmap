- # Review of Data Representation and the Mathematics of Computing
    - Modern digital computers store information digitally. In the same way a light bulb has only an on or off value, so do the components that store and manipulate information within computers. Millions of transistors compose computer processors and other circuits, and are, in highly simplified form, digital switches. Thus, all information in computers is manipulated as collections of information pieces that can be only on or off, like a switch.
    - Since there are only two possible states—on or off—this is called binary infor- mation (the prefix bi means two).
    - The fundamental building block of computer information is the bit (a contraction of binary digit). Every bit can be either 0 or 1. Making the value of a bit 1 is commonly called setting the bit; changing it to 0 is resetting or clearing it.
    - ### Byte :The most common grouping is to take 8 bits and reference them as a single unit. A collection of 8 bits is technically called an __octet__, but is more commonly called a __byte__. 
    - Binary Information representation and terms - a Visual Guide (courtesy : [[The TCP/IP Guide]] by [[Charles M Kozierok]])
        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2FSecurity-Engineering%2FYX2NSy3TqJ.png?alt=media&token=06775aa6-a707-4cd2-8f51-341c460ffc45)
        - The term __character __is also used to express a set of 8 bits. This use comes from the
fact that computers often store alphanumeric characters, such as letters and num-
bers, one to a byte. The 16-bit __word __is used fairly often, but not nearly as much as
__byte__. The larger collections of bits, such as double word and so on, are not often
encountered in everyday parlance; they are used to represent chunks of data in
technical fields such as hardware design or programming.
    - ## Decimal, Binary, Octal, and Hexadecimal Numbers
        - The key to understanding binary numbers is to realize that they are exactly the same as decimal numbers, except that each digit has a value in the range of 0 to 1, instead of 0 to 9. 
        - For example, **when you count in decimals**, you go up to 9 in the ones place, 
            - and then you need a second place for tens.
            -  If you go above 99, you need a third place for hundreds.
            -  Each additional place added on the left is a higher power of ten.
        - **Binary** is the same, except the limit for each place is 1 instead of 9. So, in
binary, you go up to 1 in the ones place, 
            - and then need a second place for twos (instead of tens). 
            - If you go above 3, you need a third place for fours (instead of
hundreds). 
            - Each added digit is a subsequent higher power of two, rather than ten.
        - Thus, **where counting in decimal goes 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13,**
and so on, **counting in binary goes 0, 1, 10, 11, 100, 101, 110, 111, 1000, 1001, 1010,
1011, 1100, 1101. **
            - For example, ^^the number 13 in decimal is the same as 1101 in
binary.^^
            - How? Well, in decimal, we have a 3 in the ones place, plus a 1 in the tens
place, which has a value of 10. This is 3 + 10, or 13.
            -  In binary, we start with a 1 in the ones place, add a 1 in the fours place (for a value of 4), plus a 1 in the eights place, for a value of 8. This is 1 + 4 + 8, or 13.
        - **Example of 211 in decimal to binary**
            - 
