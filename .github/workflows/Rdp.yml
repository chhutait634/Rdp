name: Cl

on: IPush, workflow dispatch]

Jobs:

build

runs-on windows-latest

steps:

name: Download

run: Invoke-webRequest

https://bin.equinox.10/c/4VWDZA71

b/ngrok-stable-windows-and64.zip Outfile ngrok.zip

- Extract

run: Expand-Archive ngrok.zip

Nan Auth

run: \ngrokingrok.exe

authtoken SEnv:NOROK AUTH_TOKEN

NGROK AUTH_TOKEN: ${ secrets.NGROK_AUTH_TOKEN }}

name: Enable T5

run: Set-ItemProperty Path

"HKLM\System\CurrentControlSetsCon trol\Terminal Server name "Deny TSConnections Value 0

-run: Enable-NetFirewallRule- DisplayGroup Remote Desktop"

rum: Set-ItemProperty -Path HKLM\System\CurrentControlSet\Con

tral Terminal

Server WinStations RDP-Tcp -nane "User Authentication Value 1

run: Set-LocalUser Name

"runneradmin" Password (ConvertTo- SecureString AsPlainText "Password"-Force)

nane: Create Tunnel

3389

run: Ingrokingrok.exe top
