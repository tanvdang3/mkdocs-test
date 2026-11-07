# NUC6I7KYK (Skull Canyon)

### Hardware Specifications


```
OpenBSD 8.0 (GENERIC.MP) #4: Wed Nov  4 12:16:42 CST 2026
    root@syspatch-80-amd64.openbsd.org:/usr/src/sys/arch/amd64/compile/GENERIC.MP
real mem = 34226929664 (32641MB)
avail mem = 33163497472 (31627MB)
random: good seed from bootblocks
mpath0 at root
scsibus0 at mpath0: 256 targets
mainbus0 at root
bios0 at mainbus0: SMBIOS rev. 3.0 @ 0x7b1af000 (57 entries)
bios0: vendor Intel Corp. version "KYSKLi70.86A.0067.2020.0325.1553" date 03/25/2020
bios0: Intel Corporation NUC6i7KYB
efi0 at bios0: UEFI 2.4
efi0: American Megatrends rev 0x5000b
acpi0 at bios0: ACPI 5.0
acpi0: sleep states S0 S3 S4 S5
acpi0: tables DSDT FACP APIC FPDT FIDT MCFG HPET LPIT SSDT SSDT SSDT SSDT DBGP DBG2 SSDT SSDT UEFI SSDT SSDT DMAR TPM2
acpi0: wakeup devices PEG0(S4) PEGP(S4) PEG1(S4) PEGP(S4) PEG2(S4) PEGP(S4) RP09(S4) PXSX(S4) RP10(S4) PXSX(S4) RP11(S4) PXSX(S4) RP12(S4) PXSX(S4) RP13(S4) PXSX(S4) [...]
acpitimer0 at acpi0: 3579545 Hz, 24 bits
acpimadt0 at acpi0 addr 0xfee00000: PC-AT compat
cpu0 at mainbus0: apid 0 (boot processor)
cpu0: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.19 MHz, 06-5e-03, patch 000000f0
cpu0: cpuid 1 edx=bfebfbff<FPU,VME,DE,PSE,TSC,MSR,PAE,MCE,CX8,APIC,SEP,MTRR,PGE,MCA,CMOV,PAT,PSE36,CFLUSH,DS,ACPI,MMX,FXSR,SSE,SSE2,SS,HTT,TM,PBE> ecx=77fafbbf<SSE3,PCLMUL,DTES64,MWAIT,DS-CPL,VMX,EST,TM2,SSSE3,SDBG,FMA3,CX16,xTPR,PDCM,PCID,SSE4.1,SSE4.2,x2APIC,MOVBE,POPCNT,DEADLINE,AES,XSAVE,AVX,F16C,RDRAND>
cpu0: cpuid 6 eax=27f7<SENSOR,ARAT,PTS> ecx=9<EFFFREQ>
cpu0: cpuid 7.0 ebx=29c6fbf<FSGSBASE,TSC_ADJUST,SGX,BMI1,HLE,AVX2,SMEP,BMI2,ERMS,INVPCID,RTM,MPX,RDSEED,ADX,SMAP,CLFLUSHOPT,PT> edx=bc002e00<SRBDS_CTRL,MD_CLEAR,TSXFA,IBRS,IBPB,STIBP,L1DF,SSBD>
cpu0: cpuid a vers=4, gp=4, gpwidth=48, ff=3, ffwidth=48
cpu0: cpuid d.1 eax=f<XSAVEOPT,XSAVEC,XGETBV1,XSAVES>
cpu0: cpuid 80000001 edx=2c100800<NXE,PAGE1GB,RDTSCP,LONG> ecx=121<LAHF,ABM,3DNOWP>
cpu0: cpuid 80000007 edx=100<ITSC>
cpu0: msr 10a=c04<RSBA,MISC_PKG_CT,ENERGY_FILT>
cpu0: MELTDOWN
cpu0: 32KB 64b/line 8-way D-cache, 32KB 64b/line 8-way I-cache, 256KB 64b/line 4-way L2 cache, 6MB 64b/line 12-way L3 cache
cpu0: smt 0, core 0, package 0, type P
mtrr: Pentium Pro MTRR support, 10 var ranges, 88 fixed ranges
cpu0: apic clock running at 24MHz
cpu0: mwait min=64, max=64, C-substates=0.2.1.2.4.1.1.1, IBE
cpu1 at mainbus0: apid 2 (application processor)
cpu1: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.20 MHz, 06-5e-03, patch 000000f0
cpu1: smt 0, core 1, package 0, type P
cpu2 at mainbus0: apid 4 (application processor)
cpu2: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.20 MHz, 06-5e-03, patch 000000f0
cpu2: smt 0, core 2, package 0, type P
cpu3 at mainbus0: apid 6 (application processor)
cpu3: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.20 MHz, 06-5e-03, patch 000000f0
cpu3: smt 0, core 3, package 0, type P
cpu4 at mainbus0: apid 1 (application processor)
cpu4: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.19 MHz, 06-5e-03, patch 000000f0
cpu4: smt 1, core 0, package 0, type SP
cpu5 at mainbus0: apid 3 (application processor)
cpu5: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.19 MHz, 06-5e-03, patch 000000f0
cpu5: smt 1, core 1, package 0, type SP
cpu6 at mainbus0: apid 5 (application processor)
cpu6: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.19 MHz, 06-5e-03, patch 000000f0
cpu6: smt 1, core 2, package 0, type SP
cpu7 at mainbus0: apid 7 (application processor)
cpu7: Intel(R) Core(TM) i7-6770HQ CPU @ 2.60GHz, 2494.19 MHz, 06-5e-03, patch 000000f0
cpu7: smt 1, core 3, package 0, type SP
ioapic0 at mainbus0: apid 2 pa 0xfec00000, version 20, 120 pins
acpimcfg0 at acpi0
acpimcfg0: addr 0xe0000000, bus 0-255
acpihpet0 at acpi0: 23999999 Hz
acpiprt0 at acpi0: bus 0 (PCI0)
acpiprt1 at acpi0: bus -1 (PEG0)
acpiprt2 at acpi0: bus -1 (PEG1)
acpiprt3 at acpi0: bus -1 (PEG2)
acpiprt4 at acpi0: bus -1 (RP09)
acpiprt5 at acpi0: bus -1 (RP10)
acpiprt6 at acpi0: bus -1 (RP11)
acpiprt7 at acpi0: bus -1 (RP12)
acpiprt8 at acpi0: bus -1 (RP13)
acpiprt9 at acpi0: bus 1 (RP01)
acpiprt10 at acpi0: bus 2 (RP02)
acpiprt11 at acpi0: bus 3 (RP03)
acpiprt12 at acpi0: bus -1 (RP04)
acpiprt13 at acpi0: bus 4 (RP05)
acpiprt14 at acpi0: bus -1 (RP06)
acpiprt15 at acpi0: bus -1 (RP07)
acpiprt16 at acpi0: bus -1 (RP08)
acpiprt17 at acpi0: bus -1 (RP17)
acpiprt18 at acpi0: bus -1 (RP18)
acpiprt19 at acpi0: bus -1 (RP19)
acpiprt20 at acpi0: bus -1 (RP20)
acpiprt21 at acpi0: bus -1 (RP14)
acpiprt22 at acpi0: bus -1 (RP15)
acpiprt23 at acpi0: bus -1 (RP16)
acpiec0 at acpi0: not present
acpipci0 at acpi0 PCI0: 0x00000004 0x00000011 0x00000001
"NTN0530" at acpi0 not configured
acpicmos0 at acpi0
acpibtn0 at acpi0: SLPB
"PNP0C14" at acpi0 not configured
intelpmc0 at acpi0: PEPD
state 0: 0x7f:1:2:0x00:0x0000000000000060
counter: 0x7f:64:0:0x00:0x0000000000000632
frequency: 0
state 1: 0x7f:1:2:0x00:0x0000000000000060
counter: 0x7f:64:0:0x00:0x0000000000000632
frequency: 0
acpibtn1 at acpi0: PWRB
tpm0 at acpi0 TPM_ 2.0 (CRB) addr 0xfed40000/0x5000, device 0x00000000 rev 0x0
"PNP0C0B" at acpi0 not configured
"PNP0C0B" at acpi0 not configured
"PNP0C0B" at acpi0 not configured
"PNP0C0B" at acpi0 not configured
"PNP0C0B" at acpi0 not configured
acpicpu0 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu1 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu2 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu3 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu4 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu5 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu6 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpicpu7 at acpi0: C3(200@1034 mwait.1@0x60), C2(200@151 mwait.1@0x33), C1(1000@1 mwait.1), PSS
acpipwrres0 at acpi0: PG00, resource for PEG0
acpipwrres1 at acpi0: PG01, resource for PEG1
acpipwrres2 at acpi0: PG02, resource for PEG2
acpipwrres3 at acpi0: WRST
acpipwrres4 at acpi0: WRST
acpipwrres5 at acpi0: WRST
acpipwrres6 at acpi0: WRST
acpipwrres7 at acpi0: WRST
acpipwrres8 at acpi0: WRST
acpipwrres9 at acpi0: WRST
acpipwrres10 at acpi0: WRST
acpipwrres11 at acpi0: WRST
acpipwrres12 at acpi0: WRST
acpipwrres13 at acpi0: WRST
acpipwrres14 at acpi0: WRST
acpipwrres15 at acpi0: WRST
acpipwrres16 at acpi0: WRST
acpipwrres17 at acpi0: WRST
acpipwrres18 at acpi0: WRST
acpipwrres19 at acpi0: WRST
acpipwrres20 at acpi0: WRST
acpipwrres21 at acpi0: WRST
acpipwrres22 at acpi0: WRST
acpipwrres23 at acpi0: FN00, resource for FAN0
acpipwrres24 at acpi0: FN01, resource for FAN1
acpipwrres25 at acpi0: FN02, resource for FAN2
acpipwrres26 at acpi0: FN03, resource for FAN3
acpipwrres27 at acpi0: FN04, resource for FAN4
acpitz0 at acpi0
acpitz0: critical temperature is 119 degC
acpitz1 at acpi0
acpitz1: critical temperature is 119 degC
acpivideo0 at acpi0: GFX0
acpivout0 at acpivideo0: DD1F
cpu0: using VERW MDS workaround (except on vmm entry)
cpu0: Enhanced SpeedStep 2494 MHz: speeds: 2601, 2600, 2500, 2300, 2200, 2100, 2000, 1800, 1700, 1600, 1400, 1300, 1200, 1100, 900, 800 MHz
pci0 at mainbus0 bus 0
pchb0 at pci0 dev 0 function 0 "Intel Core 6G Host" rev 0x0a
inteldrm0 at pci0 dev 2 function 0 "Intel Iris Pro 580" rev 0x09
drm0 at inteldrm0
inteldrm0: msi, SKYLAKE, gen 9
"Intel Core GMM" rev 0x00 at pci0 dev 8 function 0 not configured
xhci0 at pci0 dev 20 function 0 "Intel 100 Series xHCI" rev 0x31: msi, xHCI 1.0
usb0 at xhci0: USB revision 3.0
uhub0 at usb0 configuration 1 interface 0 "Intel xHCI root hub" rev 3.00/1.00 addr 1
pchtemp0 at pci0 dev 20 function 2 "Intel 100 Series Thermal" rev 0x31
"Intel 100 Series MEI" rev 0x31 at pci0 dev 22 function 0 not configured
ahci0 at pci0 dev 23 function 0 "Intel 100 Series AHCI" rev 0x31: msi, AHCI 1.3.1
ahci0: port 0: 6.0Gb/s
ahci0: port 3: 6.0Gb/s
scsibus1 at ahci0: 32 targets
sd0 at scsibus1 targ 0 lun 0: <ATA, Samsung SSD 860, RVT2> naa.5002538e405e5590
sd0: 476940MB, 512 bytes/sector, 976773168 sectors, thin
sd1 at scsibus1 targ 3 lun 0: <ATA, Samsung SSD 860, RVT2> naa.5002538e4031f059
sd1: 953869MB, 512 bytes/sector, 1953525168 sectors, thin
ppb0 at pci0 dev 28 function 0 "Intel 100 Series PCIE" rev 0xf1: msi
pci1 at ppb0 bus 1
ppb1 at pci0 dev 28 function 1 "Intel 100 Series PCIE" rev 0xf1: msi
pci2 at ppb1 bus 2
sdhc0 at pci2 dev 0 function 0 "O2 Micro 0Z8621 SD/MMC" rev 0x01: msi
sdhc0: SDHC 4.00, 50 MHz base clock
sdmmc0 at sdhc0: 4-bit, sd high-speed, mmc high-speed, ddr52, dma
ppb2 at pci0 dev 28 function 2 "Intel 100 Series PCIE" rev 0xf1: msi
pci3 at ppb2 bus 3
iwm0 at pci3 dev 0 function 0 "Intel AC 8260" rev 0x3a, msi
ppb3 at pci0 dev 28 function 4 "Intel 100 Series PCIE" rev 0xf1: msi
pci4 at ppb3 bus 4
pcib0 at pci0 dev 31 function 0 "Intel HM170 LPC" rev 0x31
"Intel 100 Series PMC" rev 0x31 at pci0 dev 31 function 2 not configured
azalia0 at pci0 dev 31 function 3 "Intel 100 Series HD Audio" rev 0x31: msi
azalia0: codecs: Realtek ALC233, Intel/0x2809, using Realtek ALC233
audio0 at azalia0
ichiic0 at pci0 dev 31 function 4 "Intel 100 Series SMBus" rev 0x31: apic 2 int 16
iic0 at ichiic0
spdmem0 at iic0 addr 0x50: 16GB DDR4 SDRAM PC4-19200 SO-DIMM
spdmem1 at iic0 addr 0x52: 16GB DDR4 SDRAM PC4-19200 SO-DIMM
em0 at pci0 dev 31 function 6 "Intel I219-LM" rev 0x31: msi, address 54:b2:03:0a:ad:e8
isa0 at pcib0
isadma0 at isa0
fdc0 at isa0 port 0x3f0/6 irq 6 drq 2
com0 at isa0 port 0x3f8/8 irq 4: ns16550a, 16 byte fifo
pcppi0 at isa0 port 0x61
spkr0 at pcppi0
lpt0 at isa0 port 0x378/4 irq 7
wbsio0 at isa0 port 0x2e/2: NCT6776F rev 0x33
lm1 at wbsio0 port 0xa00/8: NCT6776F
vmm0 at mainbus0: VMX/EPT
efifb at mainbus0 not configured
iwm0: restrict all mbufs to low memory
uhidev0 at uhub0 port 2 configuration 1 interface 0 "Keychron Keychron C1" rev 2.00/1.04 addr 2
uhidev0: iclass 3/1
ukbd0 at uhidev0: 8 variable keys, 5 key codes
wskbd0 at ukbd0 mux 1
uhidev1 at uhub0 port 2 configuration 1 interface 1 "Keychron Keychron C1" rev 2.00/1.04 addr 2
uhidev1: iclass 3/1, 3 report ids
ukbd1 at uhidev1 reportid 1: 120 variable keys, 0 key codes
wskbd1 at ukbd1 mux 1
uhid0 at uhidev1 reportid 2: input=1, output=0, feature=0
ucc0 at uhidev1 reportid 3: 829 usages, 20 keys, array
wskbd2 at ucc0 mux 1
uaudio0 at uhub0 port 3 configuration 1 interface 1 "ASUSTeK ASUS XONAR U5" rev 2.00/1.02 addr 3
uaudio0: clock attributes differ
uaudio1 at uhub0 port 3 configuration 1 interface 2 "ASUSTeK ASUS XONAR U5" rev 2.00/1.02 addr 3
uaudio1: clock attributes differ
uaudio2 at uhub0 port 3 configuration 1 interface 3 "ASUSTeK ASUS XONAR U5" rev 2.00/1.02 addr 3
uaudio2: clock attributes differ
uhidev2 at uhub0 port 3 configuration 1 interface 4 "ASUSTeK ASUS XONAR U5" rev 2.00/1.02 addr 3
uhidev2: iclass 3/0
ucc1 at uhidev2: 23 usages, 3 keys, enum
wskbd3 at ucc1 mux 1
ugen0 at uhub0 port 3 configuration 1 "ASUSTeK ASUS XONAR U5" rev 2.00/1.02 addr 3
ugen1 at uhub0 port 9 "Intel Bluetooth" rev 2.00/0.01 addr 4
vscsi0 at root
scsibus2 at vscsi0: 256 targets
softraid0 at root
scsibus3 at softraid0: 256 targets
root on sd0a (4c518fad408d88ab.a) swap on sd0b dump on sd0b
drm:pid0:intel_lspcon_init *ERROR* [drm] *ERROR* Failed to probe lspcon
inteldrm0: 1024x768, 32bpp
wsdisplay0 at inteldrm0 mux 1
wskbd0: connecting to wsdisplay0
wskbd1: connecting to wsdisplay0
wskbd2: connecting to wsdisplay0
wskbd3: connecting to wsdisplay0
wsdisplay0: screen 0-5 added (std, vt100 emulation)
iwm0: hw rev 0x200, fw ver 36.ca7b901d.0, address 14:4f:8a:7a:86:4a
```
