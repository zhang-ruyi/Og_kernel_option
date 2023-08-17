# modified:
    modified:   Makefile
	modified:   arch/arm/mm/mmu.c
	modified:   include/linux/compiler_attributes.h
	modified:   include/linux/compiler_types.h
	modified:   init/Kconfig
	modified:   lib/Kconfig.debug


# generate patch
    git diff > xxx.patch

# apply patch
    git apply xxx.patch

* verify with <= gcc-11  and <= aarch-gcc11
