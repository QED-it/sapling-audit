# Sapling audit

QED-it performed an audit of the Sapling release of Zcash during August 2018 and October 2018.

The audit spanned the following:
1. Reviewing the implementation of cryptographic primitives and operations on them, numeric conversions, boolean operations and hash functions. These were implemented using [bellman](https://github.com/zcash/librustzcash/tree/master/bellman) and used in [sapling-crypto](https://github.com/zcash/librustzcash/tree/master/sapling-crypto).
2. Reviewing the combination of circuits into a protocol, as implemented in [sapling-crypto](https://github.com/zcash/librustzcash/tree/master/sapling-crypto). 
3. Producing test vectors and verifying the specification by indepdently implementing the protocol ([go-jubjub](https://github.com/QED-it/go-jubjub), [juby](https://github.com/QED-it/juby), [sapling-crypto-internal](https://github.com/QED-it/sapling-crypto-internal) and [zcash-test-vectors-internal](https://github.com/QED-it/zcash-test-vectors-internal).

The report itself is available here: [sapling-audit-report.pdf](sapling-audit-report.pdf).
