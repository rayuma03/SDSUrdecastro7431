# SDSUrdecastro7431

### Rae Decastro
### sdsuRedID: 825242867
### This is a project for a 12 - 8 Hamming code with a extra parity bit as the 13th bit position. 
The 1st component is the ECC generator which accepts the original 8 bits of data then outputs 13 bit data, 5 of which are parity bits, these 5 parity bits are placed in specific bit positions within the 13 bits.
The second component is the 13 transmission which accepts the 13 bits of data from the ECC generator. This component's main funtion is to introduce single bit error or double bit errors on the 13 bit data it received from the ECC generator.
The third and last component is the main memory which receives the 13 bit data from the transmission. One function of the main memory is to detect if there is and error or lack of error during the transmission of the 13 bits of data it received. The main memory's main function is to detect a if a single bit error or a double bit error occured during the transmission. The main memory can fix a single bit error. However, if the error during the transmisson is a double bit error the main memory can only detect the error but cannot fix it.
