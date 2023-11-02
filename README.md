### Note: An alternative IEEE 754 Floating Multiplier has also been provided

# pes_crc16_parallel

A 16-bit parallel CRC (Cyclic Redundancy Check) is a method of error-checking used in digital communication systems and data storage. CRC is a widely used technique for detecting errors in data transmission and storage by appending a checksum to the data and verifying it at the receiving end.

## Iverilog and GTK Wave
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/4de26572-d10a-4b74-909b-fba5683d56be)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/f5b38f42-47e5-4895-be55-9736122fcec8)

## Yosys
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/cd4c8afb-d2ec-4ccd-9c77-c6efa7257d4c)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/e4aa42a2-4a9f-40da-9f5e-ebbb3668446c)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/e7de79f6-7be0-4d70-a392-97be819082ce)

## Gate Level Simulation
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/93771bd3-84ec-4442-b8fc-0af9bde286cd)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/79a6db78-82e7-4026-a5d5-2fdd5c253f26)

 ### This is a opensource code that was used but the GLS failed. 
 
 # An alternative design, IEEE 754 Floating Point Multiplier.

The results for the multiplier are as follows

# pes_fmul

IEEE 754 Floating Point Multiplier (32 bit). 
The code and test bench for the multiplier has also been uploaded.

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/31ab4ecd-66c0-40f0-9ed9-84fba01f6fa0)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/b3f184f8-9fd9-4c6a-b25f-1ebd231f4d87)


## Yosys


![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/d9986110-4e44-4de9-b606-d78f3de24d50)
![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/cd486440-011b-4ab1-9e28-ca6cb7e5d08b)
![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/c264a898-4cf5-48fc-b921-af6ba3ea8054)
![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/baf6f37b-56a0-4799-a4bb-9186f5b2cc9c)
![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/d45135d6-9c9d-41bc-8395-bc984ed1e809)



## GTKwave and Iverilog 

![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/91f1ee2f-bec1-43d9-ae3f-cd9a0212de8f)
![image](https://github.com/mauriya0202/pes_fmul/assets/112739882/634012b3-b091-4287-8f2a-1d8a6a8b0979)

## GLS

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/369a9e05-8553-455b-942b-334bf516d16b)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/a5e58302-c637-4a1b-b47b-b3e169d793f7)


We can see that the gate level simulation matches the behavioral simulation

# Synthesis

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/5696efa4-0641-49fa-9ff0-7a953380a9b9)

# Floorplan

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/768be5df-14fd-47c3-b879-8300110516f7)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/54be2ef3-0f2c-40b7-82ea-b87576df5ea4)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/d8583b80-8de3-4c1b-b2af-8c5e3c245d72)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/93718287-0d4f-49bc-9da0-66aa947a03ce)




# Placement

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/6b8e6d4c-3a21-4bae-9b6c-96230b8d5e85)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/7162c80e-0078-4855-b62f-dc899cdbafd6)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/c9c6f9b5-8b8c-4a0c-9b55-4fcd7bd4ee6f)


# STA

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/59f9f18a-e86b-4046-a8c8-8563f26030b6)
![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/58406d20-6f25-47ce-8dc1-031c5f1bacb1)

# cts & pdn

![image](https://github.com/mauriya0202/pes_crc16_parallel/assets/112739882/7a8881b8-1f96-4bc8-bfd1-067d7fd36c7d)


