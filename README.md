# myPathORAMSimulator

The only changes, related to the treetop, applied yet are as follows (they are between "//*********META" and "//********** End META"
1-in BinPathORam.cpp Line 167
2-in BinPathORam.cpp Line 451

There are also some functions to get stat of this data structure listed as below
    void PrintBuckets();
    bool HitInStash(uint64_t id);
    
I also modified SingleORAMTest.cpp to enable it to read the trace and more importantly removed its backgroundEviction since as Z = 4 itis not expected to get overflown. 

