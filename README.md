Please use `*.sh` scripts to run analytics (`all*.sh` for full analysis and `rels*.sh` for per release stats)
This program assumes that gitdm lives in: `~/dev/cncf/gitdm/` and kubernetes in `~/dev/go/src/k8s.io/kubernetes/`
Output files are placed in `kubernetes/` directory.

This is an iterational process:
Run any of scripts. Review its output in kubernetes directory. Iteratively adjust mappings to handle more authors (config/mappings is in
`cncf-config/`)

You can also run via `./debug.sh` to halt in debugger and review hackers structure and those who were not found. See `cncfdm.py`:`DebugUnknowns`

Final report:
Data: https://docs.google.com/spreadsheets/d/15otmXVx8Gd6JzfiGP_OSjP8M9zyLeLof5-IGQKEb0UQ/edit?usp=sharing
Report: https://docs.google.com/document/d/1RKtRamlu4D_OpTDFTKNpMsmV51obdZlPWbXVj-LrDuw/edit?usp=sharing
