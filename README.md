# Amnezia Backup Tool
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fnastyagrifon%2Famnezia-backup.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fnastyagrifon%2Famnezia-backup?ref=badge_shield)


Backs up and restores your Amnezia VPN containers.

## What it does

- Creates backup of users with date/time stamps
- Can restore from backups when needed

## How to use

### Make a backup
```bash
./amnezia-backup.sh
```

### Restore from backup  
```bash
./amnezia-backup.sh -r
```

## What you need

- Docker running on your system
- This script file
- Enough disk space for backups

## Where backups go

Backups are saved in a directory `./amnezia_opt_backups/`

## Important

- Restoring will restart your containers
- Test restores carefully 
- Keep your backups safe

## License

Free to use under GPL v3.0 license.


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fnastyagrifon%2Famnezia-backup.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fnastyagrifon%2Famnezia-backup?ref=badge_large)