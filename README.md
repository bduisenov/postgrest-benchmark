  - Start `./instantpg.sh` in one terminal
  - Run `sh setup.sh`; it should successfully finish
  - Run `./postgrest postgrest.config  > /dev/null` in another terminal
  - Run `sh pgbench.sh`, save output
  - Run `sh ab.sh`, save output
  - Run `sh wrk.sh`, save output
