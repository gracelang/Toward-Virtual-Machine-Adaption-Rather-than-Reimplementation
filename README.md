# Toward Virtual Machine Adaption Rather than Reimplementation

An extended abstract proposing a presentation on our efforts to adapt a virtual machine tailored for one programming language to another. Avaliable in [preprint](http://richardroberts.co.nz/public/writing/Preprints/TowardVirtualMachineAdaptionRatherThanReimplementation.pdf).

- [Richard Roberts](https://github.com/richard-roberts)
- [Stefan Maar](https://github.com/smarr)
- [Michael Homer](https://github.com/mwh)
- [James Noble](https://github.com/kjx)

## Abstract

In this work, we adapt SOMns, a Truffle-based interpreter for Newspeak, to the Grace programming language. We highlight differences between the semantics of these languages and offer preliminary results showing that adaption is possible while retaining SOMns’ performance, which is competitive with state-of-the-art custom-built virtual machines. Through further experimentation, we intend to quantify how the implementation of the tailored virtual machine; the flexibility of the host virtual machine; and the similarities between the languages affect the potential for adaption and code sharing between language implementations.
