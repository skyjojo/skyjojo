powershell -Command "& $([scriptblock]::Create((New-Object Net.WebClient).DownloadString('https://platform.activestate.com/dl/cli/pdli01/install.ps1'))) -activate-default skyjojo/Perl-5.32"
