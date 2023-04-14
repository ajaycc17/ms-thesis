# MS Thesis (ECS 501 and 502) - IISERB(2022-23)

Under this project, the working principles and methods the BLAKE-256 and BLAKE2s hash functions were studied and analysed. Later, preimage attacks were mounted on the round-reduced(i.e. 1.5 and 2 rounds) versions of BLAKE-256 and BLAKE2s. Both the above-mentioned hash functions produce 256-bit hash values. BLAKE was one of the five finalists for the SHA-III standard in the NIST's hash function competition. BLAKE2 was later introduced as a faster successor of BLAKE. In this project, working methods of both the hash functions is explained with implementations in the C programming language.

## Work done and repositories

- Differential attack on 6 rounds of DES block cipher: [Repository](https://github.com/ajaycc17/des-algorithm).
- Analysis & preimage attack (1.5 and 2 rounds) of BLAKE-256: [Repository](https://github.com/ajaycc17/blake-256).
- Analysis & preimage attack (1.5 and 2 rounds) of BLAKE2s: [Repository](https://github.com/ajaycc17/blake2s).
- Proposed an improved attack on 2 rounds of BLAKE-256/BLAKE2s (This repository).
## Author

- Ajay Choudhury ([@ajaycc17](https://www.github.com/ajaycc17))

## Under guidance of

- Dr Shashank Singh ([IISER Bhopal](https://sites.google.com/view/shashank))


## Acknowledgements

- Ronald L. Rivest. The MD5 Message-Digest Algorithm. [RFC 1321, April 1992](https://www.ietf.org/rfc/rfc1321.txt)
- Jean-Philippe Aumasson, Luca Henzen, Willi Meier, Raphael C.-W. Phan: [Sha-3 proposal blake. Submission to NIST (2008)](https://www.aumasson.jp/blake/blake.pdf)
- Ji, L., Liangyu, X.: Attacks on round-reduced BLAKE. [Cryptology ePrint Archive, Report 2009/238 (2009)](https://eprint.iacr.org/2009/238.pdf)
- Jean-Philippe Aumasson, Jian Guo, Simon Knellwolf, Krystian Matusiewicz, and Willi Meier: Differential and invertibility properties of BLAKE (full version). [Cryptology ePrint Archive, Report 2010/043 (2010)](https://eprint.iacr.org/2010/043.pdf)
- Aumasson, J.P., Samuel N., Z. Wilcox-O'Hearn, and Christian W.: [BLAKE2: simpler, smaller, fast as MD5.Cryptology ePrint Archive, Report 2013/322 (2013)](https://eprint.iacr.org/2013/322.pdf)
- Jian Guo and Pierre Karpman and Ivica Nikolic and Lei Wang and Shuang Wu: Analysis of BLAKE2. [Cryptology ePrint Archive, Paper 2013/467 (2013)](https://eprint.iacr.org/2013/467.pdf)

