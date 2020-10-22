# SDSUrdecastro7431

### Rae Decastro
### sdsuRedID: 825242867
### This is a project for a 12 - 8 Hamming code with a extra parity bit as the 13th bit position. 
This project has 3 components the 1st compnent is the ECC generator which accepts the original 8 bits of data then outputs 13 bit data, 5 of which are parity bits. The 5 parity bits are placed in specific bit positions within the 13 bits.
The second component is the 13 transmission which accepts the 13 bits of data from the ECC generator. This component's main funtion is to introduce single bit error or double bit errors on the 13 bit data it received from the ECC generator.
The third and last component is the main memory which receives the 13 bit data from the transmission. The function of the main memory is to detect if there is and error or no error on the 13 bits of data it receives. The main memory can detect a single bit error and fixes that single bit error. It can also detect a double bit error but cannot fix the error if the error is a 2 bit error.
