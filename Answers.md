Explain in detail the workings of a dynamic array:
* What is the runtime complexity to access an array, add or remove from the front, and add or remove from the back?
    The runtime complexity to access an array is O(1), add or remove from the front is O(n) and remove from the back is O(1).

* What is the worse case scenario if you try to extend the storage size of a dynamic array?
    The worse case scenario if you try to extend the storage size of a dynamic array is O(n).

Explain how blockchain networks remain in consensus:
* What does a node do if it gets a message from another in the network with a new block?
    If a node gets a message from another in the network with a new block, the will send an iventory message to announce the new blow to it's peers. The peers then respond by sending a get data message requesting the header or the complete block. The nodes then check the header and the transaction for adherence to the rules.

* Why can't someone cheat by changing a transaction from an earlier block to give themselves coins?
    Transactions cannot be changed without changing all of the subsequent transactions as well. All transactions include a digital signature that uses your private key and the text of the message itself. All of the transaction-processing nodes are able to use a function to check that the digital signature corresponds with the public key.