File _h.c_ generates Matrix (s * s):
    1) gcc h.c -o h.out
    2) ./h.out <s>
    3) and there is _mm.bin_ file with Matrix (s * s) inside it
Then you should run _main.c_:
    1) gcc -pthread main.c
    2) ./a.out <num_threads>
    3) output contains:
        # MAXIMUM
        # indexes of MAXIMUM
        # MINIMUM
        # indexes of MINIMUM