Project Overview – Wireless video transmission in a extremely lossy environment using Polar Coding error correction technique

Project Approach – Use 2 Software Defined Radio platforms as transmitter and receiver to stream video information. Encoding and Decoding of the information being sent will be done based on Polar Codes. This forward error correction block will be implemented in the GNURadio platform.

Project Objectives: To find the digital modulation technique and image compression techniques which are better for Polar Code error correction mechanism in a wireless environment. 

Milestones: 
1. USRP implementation of Polar Code Encoder. Output of the encoder can be shown in a file saved.
2. USRP implementation of Polar Code Decoder. Decoder input can be fed from a file, after decoding, information will be generated. 
3. Sending information via SDRs(wireless interface) and prepare the BER evaluation testbench at the receiver.
4. Change different modulations on the encoder and decoder. Analyze the BER performance of these modulation schemes: BPSK, QAM, OFDM. 
Plot modulation scheme vs BER performance graph to understand which is better for which scenarios.
5. Change the image encoding scheme and figure out which is best for the Polar Code based on the BER performance. Plot encoding scheme vs BER performance.
6. Stream video based on the MJPEG and evaluate the BER performance.

How it will be done? The project involves writing a C++ code of the Polar Code encoder and decoder targeted for the GNURadio platform. Then arranging the blocks of digital modulation scheme in the GNURadio platform to send information and receive information. 

Software: GNURadio Companion, Matlab 

Hardware: USRP B/N series - 2, 2 machines to do the packet processing. 
The hardware and software are available in the Embedded Systems laboratory and also in my lab. 

Testing: Image of different formats would be taken and sent via the wireless medium in the lab. To add more noise, GNUradio platform will be used. BER will be calculated at the receiver using MATLAB or GNURadio platform itself if feasible.
