## IPV4 - Internet Protocolo Version 4
    
    IPV4 - Examples 172.160.13.1, 192.172.0.1, 10.0.2.1, 100.25.3.5, 78.25.65.1

## Groups
    
    IPV4 consists of four groups <group1> . <group2> . <group3> . <group4> 
    Which represents the IP address of above examples (172.160.13.1)

## Bits
    
    Each group is validated as 8 bits, Then the entire IPV4 is considered as 8 bits * 4 groups = 32 bits

## Group Limit
   
    In IPV4 each group has a limit of 255, It will represent as 255.255.255.255 

## IPV4 allocating the I.P addresses
    
     IP addresses are allocated by mentioning the bit size, Example: 10.0.0.0/24, 192.168.0.1/16 etc..

     
     10.0.0.0/24 means 24 bit divided by 8 bit size = 3 groups, It means 3 groups are blocked and one group is available to use. It means 1 group represents 255 numbers - 255 I.P addresses are available to use.
     Example: 10.0.0.1, 10.0.0.2, 10.0.0.3 ………………………..10.0.0.255
     
     10.0.0.0/16 means 16 bit divided by 8 bit size = 2 groups, It means 2 groups are blocked and 2 groups are available to use. It means each group has 255 numbers - 255 group3 possibility * 255 group4 possibility (Number of ways)

## Calculation part for above explanation

             Formula:
      2^(<bits allocated> - 32)   
      
      (^ means Power of)
      
      2^(16-32) = 2^(16) = 65,536


   From above calculation we have output of 65,536, which represents we have possibility to create 65,536 I.P addresses for 16 bit IPV4


## Cheat_Sheet

     10.0.0.0/1 = 2,147,483,648


     I.P addresses are available to use
     10.0.0.0/2 = 1,073,71,824 I.P addresses  are available to use
     10.0.0.0/4 = 268,485,456 I.P addresses  are available to use
     10.0.0.0/8 = 16,777,216 I.P addresses  are available to use
     10.0.0.0/16 = 65,536 I.P addresses  are available to use
     10.0.0.0/24 = 256 I.P addresses  are available to use
     10.0.0.0/31 = 1 I.P address  are available to use
     10.0.0.0/32 = No I.P address is available to create - Gives an error



