all:
	checkmodule -m -M -o httpd_manage_syncthing_rw.mod httpd_manage_syncthing_rw.te
	semodule_package -m httpd_manage_syncthing_rw.mod -o httpd_manage_syncthing_rw.pp

clean:
	rm -f httpd_manage_syncthing_rw.mod httpd_manage_syncthing_rw.pp

install:
	semodule -i httpd_manage_syncthing_rw.pp
