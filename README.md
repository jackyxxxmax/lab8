(1)不會，因為執行之後出現terminate called without an active exception
Aborted (core dumped)，代表throw之後沒有找到catch，接著呼叫terminate function，
直接終止程式，所以不會印出。

(2)
不會，因為執行之後出現terminate called after throwing an instance of 'double'
Aborted (core dumped)，代表throw之後的數字預設為double type，而catch只能接float type，
接著呼叫terminate function，直接終止程式，所以不會印出。

(3)compile: make
   execute: ./lab8

