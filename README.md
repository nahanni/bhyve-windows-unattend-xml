# bhyve Windows AutoUnattend scripts

These template scripts are used to install Windows in unattended mode on FreeBSD bhyve. Depending on the version of Windows, you may need to apply your product keys to the XML file.

You should also change the Administrator's password.

The scripts partition the Windows disk appropriately for booting from EFI under bhyve.

Change the name of the script fo the Windows version you are installing to AutoUnattend.xml and copy it to the Windows install ISO image.
