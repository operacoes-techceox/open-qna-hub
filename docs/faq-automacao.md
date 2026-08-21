# FAQ — Automacao sem sessao interativa

**P: cron ou systemd timers para scripts de madrugada?**

R: Prefira systemd timers: logs via journalctl, controle de dependencias, restart em falha e independencia de sessao interativa. Combine com flock no script para evitar concorrencia.