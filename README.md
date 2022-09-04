- Just Trying out TinyTapeout - Go to https://tinytapeout.com for instructions!
</br>

# 2-Bit Adder, Multiplier and Comparator

- This Logic Design mainly contains an 2-bit Adder and a 2-bit Mutliplier.
- The Adder can also perform subtraction using 2's complement and the subtraction results are used to compare two 2-bit numbers (whether they are equal, greater or lesser than other). 
- This design does not contain a 2-bit comparator.

- The results from adder and multiplier are muxed and stored in D-Flip Flops (only when load is enable or logic-1 because the clk of DFF is clock gated) 
- Inputs
   - in[1] = clk
   - in[2] = load
   - in[3] = A[0]
   - in[4] = A[1]
   - in[5] = B[0]
   - in[6] = B[1]
   - in[7] = sel[0]
   - in[8] = sel[1]

### Logic Design in Wokwi - https://wokwi.com/projects/341524192738411090
![image](https://user-images.githubusercontent.com/84563214/188326522-5c286e24-babc-43f0-8070-86adcc182a46.png)

### GDSII of the Logic Design (Openlane, Skywater 130nm PDK used)
![gds_render](https://user-images.githubusercontent.com/84563214/188326515-eec373c3-b434-4543-a390-9b3675d59678.svg)
 

