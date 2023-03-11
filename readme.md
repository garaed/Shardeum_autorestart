This script check status of your node and restart it automatically when node stoped


Create new screen for run script
```
screen -S shardeum_restart
```

Run script inside screen 
```
wget -q -O shardeum_restart.sh https://raw.githubusercontent.com/garaed/Shardeum_autorestart/main/shardeum_restart.sh && chmod +x shardeum_restart.sh && sudo /bin/bash shardeum_restart.sh
```

Dettach screen 
``` Ctrl+A  D ```
