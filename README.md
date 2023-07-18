# brave
$source = 'https://github.com/gitcuan/brave/raw/main/BraveBrowserSetup.exe'

$destination ="c:\\Users\User1\Downloads\iki.exe"

Invoke-WebRequest -Uri $source -OutFile $destination
