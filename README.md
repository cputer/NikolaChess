Nikola Chess
============

http://nikolachess.com  GPU based Supercomputer Chess Engine


Introduction
============

Nikola Chess (to be referred to as codename “NIKOLA Chess” from here on) is a last generation supercomputer chess engine based on CUDA technology developed by Nvidia. Project Nikola has one purpose only and that is to make a dream come true of finding a missing like for computerized chess – human strategy. Nikola represent the final stage in chess versions based on AI we have been anticipating all of this time. This supercomputer solution is to mark a new era of computer chess engines unprecedented and unparalleled in human history. Chess represents at the same time the first and final test which AI has to pass in order to get recognition for its potentials and achievements. 


Technology
==========

Nikola will use RDMA or a direct memory access which allows interaction from the memory of one computer into that of another without involving either one's operating system. This permits high-throughput, low-latency networking, which is especially useful if millions of computers worldwide interconnect into a huge cluster. In other words, Nikola will allow uniting all chess computers with CUDA supported cards of the world into one gigantic cluster for this purpose. Additionally, Nikola will use new parallel algorithms never used before. They are based on CUDA which a C-like language that allows programmers to “easily” port their code for use on the GPU. Thanks to CUDA it will be possible for Nikola to use direct parallel storage architecture and media storage parallel file system (PFS).


Patents
=======

CPUTER company holds patents on algorithms for a funtional application.

Results
=======

End Game Analysis Calculation based on 3 repetition rule and 50 consecutive moves rules of FIDE:

No number moves-|------maximum--------|-----number-------------------|                                      
----------------|---------------------|------------------------------|              
1---------------|-----5---------------|-----3775852872---------------|                                            
2---------------|-----10--------------|-----7.30398216506453x10^16---|                                            
3---------------|-----15--------------|-----1.51577893358687x10^23---|                                            
4---------------|-----20--------------|-----7.69827064587585x10^28---|                                            
5---------------|-----25--------------|-----1.42404361906059x10^34---|                                            
6---------------|-----30--------------|-----1.21138616306393x10^39---|                                            
7---------------|-----35--------------|-----5.51777898897728x10^43---|                                            
8---------------|-----40--------------|-----1.49693269286536x10^48---|                                            
9---------------|-----45--------------|-----2.61553428261307x10^52---|                                            
10--------------|-----50--------------|-----3.12407154730694x10^56---|
 No                        number moves     Max
    1                      34,5/35          3775852872
    2: Carballo-0.7.11     23,5/35          7.30398216506453x10^16
    3: OliThink-5.3.2      22,5/35 00000 001=1 ····· 00110 11101 11011 11111 11111  274,75
    4: Mediocre-0.3.4      17,5/35 00000 00000 11001 ····· 11001 01011 11=11 11101  210,50
    5: Carballo-0.5        15,0/35 00000 01010 00010 00110 ····· =1100 010=1 11111  184,50
    6: FrankWalter-1.0.8   14,0/35 00000 0000= 00100 10100 =0011 ····· 11011 10111  158,75
    7: Bremboce-0.6.2      8,0/35  00000 10010 00000 00=00 101=0 00100 ····· 00011  117,25
    8: ArabianKnight-1.0.9 5,0/35  00000 00000 00000 00010 00000 01000 11100 ·····   55,50

Authors
=======

CPUTER http://cputer.com
