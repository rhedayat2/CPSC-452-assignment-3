# CPSC-452-assignment-3

For CSUF Cryptography with Mikael Gofman for Spring 2020

Students: 

Rahin Hedayat rhedayat2@csu.fullerton.edu 

Esteban Montelongo EstebanMontelongo@csu.fullerton.edu 

Kayla Nguyen knguyen1170@csu.fullerton.edu 

Daniel Pestolesi Danpestolesi@csu.fullerton.edu



Program completed in Python

Instructions to Execute Code:

  1. Open terminal and change to program directory
  
  2. Run program by entering:
      
      ```python signer.py <KEY FILE NAME> <SIGNATURE FILE NAME> <INPUT FILE NAME> <MODE>>```
     
     For example:
     
     to sign:
        
        ```python signer.py privKey.pem signature.sig input.txt sign```
     
     to verify:
        
        ```python signer.py pubKey.pem signature.sig input.txt verify```
