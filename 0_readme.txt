First, intall the 2 Microsoft Visual C++, they are in folder 0RequisitesInstall

On Apache folder, open httpd.conf:
Set SRVROOT      on line 39
Set DocumentRoot on line 260  #Path to projects folder
Set Directory    on line 261  #Path to project folder

On PHP folder, open php.ini
Set extension_dir on line 754  #Path to php extension dir folder

Open control panel, open system, open advanced, open environment variables
On path, include PHP folder, example C:\WebServer\PHP7313
save and restart

Open apache folder, open bin, run prompt comand, run httpd.exe or in powershell ./httpd.exe