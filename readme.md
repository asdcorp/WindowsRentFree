Windows Rent Free
=================
Make Windows 10/11 live rent free on your computer.

Prepartion
----------
* Check the `keys.md` file for the required key and a ticket file for your desired edition
* Download the required ticket file from the `tickets` directory

Activation
----------
1. Open the command prompt as an administrator
2. In the command prompt run `slmgr.vbs -ipk YOUR_KEY`
3. Copy the downloaded ticket to `C:\ProgramData\Microsoft\Windows\ClipSVC\GenuineTicket`
4. In the command prompt run `clipup -v -o`
5. In the command prompt run `slmgr.vbs -ato`
6. Windows now lives rent free on your PC.
