all:
	checkmodule -m -M -o gost.mod gost.te
	semodule_package -m gost.mod -o gost.pp

clean:
	rm -f gost.mod gost.pp

install:
	semodule -i gost.pp
