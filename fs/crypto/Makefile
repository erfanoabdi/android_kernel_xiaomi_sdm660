obj-$(CONFIG_FS_ENCRYPTION)	+= fscrypto.o

ccflags-y += -Ifs/f2fs

fscrypto-y := crypto.o fname.o hooks.o keyinfo.o policy.o fscrypt_ice.o
fscrypto-$(CONFIG_BLOCK) += bio.o
