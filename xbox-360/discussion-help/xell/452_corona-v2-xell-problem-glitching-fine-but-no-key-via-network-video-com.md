# Corona V2 XeLL problem. Glitching fine but no key via network/video/com

## 2016-03-09 09:41:30, posted by: <Unknown User>

So I have a Corona V2 refusing to boot Xell.  
   
 I'm aware of the problems in 2012 where by there was no video output (ana disabled/enabled) but I'm under the impression this has been resolved in the latest bin files and the file sets provided within J-Runner and to be honest my error looks different anyway so i'm left wondering if there is a 4GB version of the EEC out there that might get me key info to build freeboot images and if they will even boot.  
   
 In J-Runner I have:  
 Installed R/W kit and set to R/W  
 Dumped the NAND  
 Glitch2 auto selected  
 CR4 manually selected  
 Create ECC  
 Wrote ECC  
 Switched TX R/W kit back to X360  
 Powered off  
 Installed Matrix PCB configured as Project Muffin CR4 method  
 Powered on and tested a couple of timing files  
 Its pretty much instant boot, there are no problems writing stock back to it and booting retail so soldering is solid I have done 100s of RGH and at least 20 V2s without a hitch.  
   
 The com port output is below:  
   
 [code]Port opened at 09/03/2016 00:20:54 XeLL - First stage * Attempting to wakeup all CPUs... CPUs online: 01.. CPUs online: 3f.. * success. * Decompressing stage 2... * Loading ELF file... 0x00000000 0x0005cd98, Loading .text...done 0x0005cd98 0x00000814, Loading .elfldr...done 0x0005d5b0 0x00009108, Loading .data...done 0x000666b8 0x000002e4, Loading .got2...done 0x000669a0 0x00000064, Loading .sdata...done 0x00066a08 0x000077ac, Loading .rodata...done 0x0006e1b4 0x000000ec, Loading .eh\_frame\_hdr...done 0x0006e2a0 0x000005d4, Loading .eh\_frame...done 0x0006e900 0x006994e8, Clearing .bss...done 0x00707de8 0x000000d8, Clearing .sbss...done * GO (entrypoint: 0000000000007600) Logging enabled... ANA Dump before Init: unknown SMC bulk msg: 40 DVD cover state: 62 0x00000000, 0x0000001b, 0x00000000, 0x00000000, 0x00000000, 0xffffffff, 0x00000000, 0x00000000, // 00 0x00000000, 0x00000000, 0x00000000, 0xffffffff, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 08 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 10 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0xffffffff, // 18 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 20 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 28 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 30 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 38 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 40 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 48 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, // 50 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // 58 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // 60 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xdeadbeef, 0x00000000, 0x00000000, // 68 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00001001, 0x00011a78, 0x00000000, // 70 0x00000000, 0x00000000, 0xdeadbeef, 0x00000000, 0x00000000, 0xffffffff, 0xffffffff, 0x00000035, // 78 0xffffffff, 0xffffffff, 0x00000000, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // 80 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // 88 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // 90 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // 98 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // a0 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // a8 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // b0 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // b8 0xffffffff, 0xffffffff, 0x00000000, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // c0 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0x00018232, 0x1c7890e7, 0x4044acc0, // c8 0x08244080, 0x00ff00ff, 0x02d90000, 0x1b015595, 0x00000000, 0x00000000, 0x00000000, 0x0000003f, // d0 0x0000003f, 0x00000000, 0x00000002, 0x01f001f0, 0x000001f0, 0x00ffafff, 0x00001000, 0x00000000, // d8 0x00000000, 0x00000000, 0x00000000, 0x80217005, 0x00000000, 0x02000063, 0x02000063, 0x02000063, // e0 0x00000000, 0x00000000, 0x00000000, 0x03bd03b2, 0x000003bd, 0x000003ac, 0x02000063, 0x0000019a, // e8 0x026b026b, 0x026b026b, 0x00000000, 0x00000000, 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, // f0 0xffffffff, 0xffffffff, 0xffffffff, 0xffffffff, 0x00000000, 0x00000000, 0x00020003, 0x00000000, // f8 Xenos GPU ID=5841 Detected Corona motherboard! AVPACK detected: 1d[/code]