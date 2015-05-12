# lubuntu
snippets for  better lubuntu 

/etc/fstab
//servername/sharename /mountdirectory smbfs credentials=/home/myhomedirectory/.smbpasswd 0 0

create ~/.smbpasswd:
<br>
<code>
cd
echo username=mywindowsusername > .smbpasswd
echo password=mywindowspassword >> .smbpasswd
chmod 600 .smbpasswd
</code>
