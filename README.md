timechain projects
=====================

a collection of abstracts, architecture outlines, whitepapers, and codebases.


encryption
=====================

####
decrypt and overwrite:

	rm -rf ./decrypted; gpgtar --decrypt --directory ./ encrypted.tar

encrypt, overwrite, and git add:

	gpgtar --encrypt --output encrypted.tar -r bitcoinssg@gmail.com decrypted; git add -A

ensure encryption of sensitive data before repo push


installation / requirements
=====================
linux:

	sudo apt-get install -y gpg git gpgtar

failsafe measures
=====================
directory decrypted is always ignored (see .gitignore)

author 
=====================
gaurav rana

pgpkey: 
	CF1E7DC6B92DE45FBD8A777B0CA3D94203827CB3

trust minimized chronometer Bitcoin pubkeyhash: 
	1GAURAV1vQPQ8zc9hRPEipoVGjCYfDWJEm

email:
	bitcoinssg@gmail.com

