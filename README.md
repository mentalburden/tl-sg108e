# Taking a dumparooski from a TPlink TL-SG108E "unmanaged switch" (even though it has a management UI...)

SOIC8 flash rom near the cpu to a buspirate, dumped with flashrom to "chonk.bin". Not seeing a file system, and I dont think the controller has the horsepower to run a kernel anyways. Hexdump -C from chonk.bin shows a buncha web files. Took a burp and confirmed most everything is running through a few JS scripts. 
