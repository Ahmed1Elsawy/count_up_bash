# count_up_bash
a count up timer for bash

just press `s` to stop and any key to start again.

    x=1; while true; do echo $x; read -t1 -s -n1 c; if [[ "$c" == "s" ]]; then read -n1 -s c; ((x++)); sleep 1; else ((x++)); fi; done
