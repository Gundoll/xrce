TARGET := xrce

all:
	$(foreach target,$(TARGET), make -f GNUmakefile.$(target) all;)

clean:
	$(foreach target,$(TARGET), make -f GNUmakefile.$(target) clean;)
