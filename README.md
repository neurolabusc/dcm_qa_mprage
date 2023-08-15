## About

`dcm_qa_mprage` is a simple DICOM to NIfTI validator script and dataset. It illustrates several popular [MP-RAGE](https://mriquestions.com/mp-rage-v-mr2rage.html) (Magnetization Prepared - RApid Gradient Echo) sequences acquired on a 3T Siemens Prisma running VE11. Data includes a MP2RAGE (which uses two inversion times) and multi-echo [ME-MPRAGE](https://surfer.nmr.mgh.harvard.edu/fswiki/UserContributions/FAQ#Q.Isitrecommendedthatpeopleusememprage.3FHowaretheyanalyzed.3FJustsqrtsumsqroftheechoes.3FOristheresomethingmoreelaborate.3F) sequences.

Details

 - `t1_mp2rage_sag_p3_32` : 0.8mm isotropic, GRAPPAx3 TR 5000ms, TIs 822 and 2500ms, TE 3.1ms.
 - `HCP_T1` : 0.8mm isotropic, GRAPPAx2 TR 2400ms, TI 1060ms, TE 2.2ms.
 - `T1_mprage_ns_sag_p2` : 1.0mm isotropic, GRAPPAx2 TR 2250ms, TI 925ms, TE 4.1ms.
 - `T1_memprage_5` : 1.0mm isotropic, GRAPPAx2 TR 2530ms, TI 1100ms, TEs 1.4, 2.9 , 4.4, 5.8, 7.3ms. Each echo saved individually.
 - `T1_memprage_rms` : 1.0mm isotropic, GRAPPAx2 TR 2530ms, TI 1100ms, TEs 1.4, 2.9 , 4.4, 5.8, 7.3ms. Echoes averaged and saved as single Root Mean Square image.

## Running

Assuming that the executable dcm2niix is in your path, you should be able to simply run the script `batch.sh` from the terminal.

