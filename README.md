
See the live version @ [`bitsblocks.github.io/bitcoin-whitepaper`](http://bitsblocks.github.io/bitcoin-whitepaper)

---


# Bitcoin White Paper - A Peer-to-Peer Electronic Cash System (Manuscripts Book Edition)



by Satoshi Nakamoto

> Note: This is the original document reformatted in a single-page book edition
>  (using the [Manuscripts format](http://manuscripts.github.io)).


**Abstract.** A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution. Digital signatures provide part of the solution, but the main benefits are lost if a trusted third party is still required to prevent double-spending. We propose a solution to the double-spending problem using a peer-to-peer network. The network timestamps transactions by hashing them into an ongoing chain of hash-based proof-of-work, forming a record that cannot be changed without redoing the proof-of-work. The longest chain not only serves as proof of the sequence of events witnessed, but proof that it came from the largest pool of CPU power. As long as a majority of CPU power is controlled by nodes that are not cooperating to attack the network, they'll generate the longest chain and outpace attackers. The network itself requires minimal structure. Messages are broadcast on a best effort basis, and nodes can leave and rejoin the network at will, accepting the longest proof-of-work chain as proof of what happened while they were gone.


- [Introduction](index.md#introduction)
- [Transactions](index.md#transactions)
- [Timestamp Server](index.md#timestamp-server)
- [Proof-of-Work](index.md#proof-of-work)
- [Network](index.md#network)
- [Incentive](index.md#incentive)
- [Reclaiming Disk Space](index.md#reclaiming-disk-space)
- [Simplified Payment Verification](index.md#simplified-payment-verification)
- [Combining and Splitting Value](index.md#combining-and-splitting-value)
- [Privacy](index.md#privacy)
- [Calculations](index.md#calculations)
- [Conclusion](index.md#conclusion)
- [References](index.md#references)



## Meta

### Sources

See the [original document (PDF)](https://bitcoin.org/bitcoin.pdf) (~180 KiB).
