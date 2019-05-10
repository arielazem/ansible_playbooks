# ansible_playbooks

#md5 algorithm
echo 'joske' | openssl passwd -1 -stdin

#sha512 algorithm
python3 -c ‘import crypt; print(crypt.crypt(“MyAdminPass”, crypt.mksalt(crypt.METHOD_SHA512)))’
