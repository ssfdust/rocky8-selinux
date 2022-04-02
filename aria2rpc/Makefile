all:
	checkmodule -m -M -o aria2rpc.mod aria2rpc.te
	semodule_package -m aria2rpc.mod -o aria2rpc.pp

clean:
	rm -f aria2rpc.mod aria2rpc.pp

install:
	semodule -i aria2rpc.pp
