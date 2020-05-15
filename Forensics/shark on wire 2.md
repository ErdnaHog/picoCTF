## Title:

shark on wire 2

## Description:

We found this [packet capture](https://2019shell1.picoctf.com/static/dcd259894e0efe9d6e91da2af47e6369/capture.pcap). Recover the flag that was pilfered from the network. You can also find the file in /problems/shark-on-wire-2_0_3e92bfbdb2f6d0e25b8d019453fdbf07.

## Initial Thought Process + Why didn't it work + Solution :

I already attempted the previous challenge that required me to use wireshark. I filtered out only udp packets. Filtered its length, filtered its destination.

![result after filtering on wireshark](.\result after filtering on wireshark.png)

It didnt work because I am looking at the wrong address. Still unsolved (15/5/2020)

## Learning takeaway:

I learnt how to filter in wireshark.