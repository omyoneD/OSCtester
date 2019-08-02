# OSCtester

## Dependencies

This role has no dependencies unless keytabs generated on kerberos role

## Example Playbook

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:


	- name: Mount NFS
	  import_role:
        name: tools/nfs
	  vars:
	    nfs_server: "{{ isilon.smart_connect }}"
        nfs_remote_path: "{{ isilon.root_path }}/MSTR_shared_cache"
	    nfs_mount_path: "/var/opt/MicroStrategy/shared_cache"

[cosas](../../../$rol/README.md)
[otrascosas](../../../$rol/README.md) ![#ff0000](PENDING)
