# SAXS dataset for data analysis tutorial

## Composition of the dataset

This dataset includes processed (radially averaged and mask-corrected) SAXS data from a sample of hen egg white lysozyme. The concentrations used were:

- 8 mg/ml (`02700_F2-T1_lys_8*.dat`)
- 4 mg/ml (`02702_F2-T1_lys_8*.dat`)
- 2 mg/ml (`02704_F2-T1_lys_8*.dat`)
- 1 mg/ml (`02706_F2-T1_lys_8*.dat`)
- buffer (`02698_F1-T1_buff_lys*.dat`)

Data can be found in the `processed` folder.


## Experimental conditions

Ten frames were acquired during 120 seconds at 20 °C in the MAXS configuration (detector distance from sample of 600 mm).

The data was acquired on 2019-12-17 by [Normand Cyr](https://www.github.com/normcyr) at the [Structural Biology Platform](https://biochimie.umontreal.ca/plateformes-scientifiques-bmm/biologie-structurale/) of the Université de Montréal.

- Instrument: Xenocs BioXolver L
- X-rays generator: Excillum MetalJet D2+ 70 kV (λ = 1.34 Å)
- Detector: Dectris PILATUS3 R 300K


## Additional sample information

The buffer used was 20 mM Tris pH 7.5, 150 mM NaCl.

The full sequence of lysozyme is:

```
>sp|P00698|LYSC_CHICK Lysozyme C OS=Gallus gallus OX=9031 GN=LYZ PE=1 SV=1
MRSLLILVLCFLPLAALGKVFGRCELAAAMKRHGLDNYRGYSLGNWVCAAKFESNFNTQA
TNRNTDGSTDYGILQINSRWWCNDGRTPGSRNLCNIPCSALLSSDITASVNCAKKIVSDG
NGMNAWVAWRNRCKGTDVQAWIRGCRL
```

See UNIPROT entry [P00698](https://www.uniprot.org/uniprot/P00698) for more details.

The sample used for the SAXS experiments comprises amino acids 19 to 147 of the protein. Many X-ray crystal structures exist in the PDB. A good example is entry [1BWH](https://www.rcsb.org/structure/1BWH).
