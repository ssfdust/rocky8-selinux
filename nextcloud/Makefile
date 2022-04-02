all:
	checkmodule -m -M -o nextcloud.mod nextcloud.te
	semodule_package -m nextcloud.mod -o nextcloud.pp

clean:
	rm -f nextcloud.mod nextcloud.pp

install:
	semodule -i nextcloud.pp
