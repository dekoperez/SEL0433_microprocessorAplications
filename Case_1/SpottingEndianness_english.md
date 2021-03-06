# Estudo de Caso: Spotting Endianness

Andrew, on his search for internship, got an interview in a software company. During the technical interview, the software engineering responsible for it proposed the following problem:

> “Create a function to verify if a 32-bit processor uses little or big endian without knowing its designer. You can use the programming language of your choice. ”

Andrew knew what <i>endianness</i> was, but he didn't know that a <i>little endian</i> processor "corrects" the data on every movement instruction, thus making its <i>endianness</i> invisible for the programmer.

## Part A

In assembly, make this function for the processor used on this class. Return 0 on the F0 flag if it is <i>big endian</i> or 1 if it is <i>little endian</i>.

## Part B

In C, make this function for the specified architecture using the C90 standard and assume that every IDE used for processor programming compile C on this standard, allowing then the function to be used on every processors. Return 0 if the processor is <i>big endian</i> or returns 1 if it is <i>little endian</i>.
