Here's the general workflow: 

- [RmanRecoveryInformation.sql](https://github.com/karlarao/scripts/blob/master/backup_and_recovery/RmanRecoveryInformation.sql) - start with this SQL to assess the recovery situation 
- [RmanBlockCorruption.sql](https://github.com/karlarao/scripts/blob/master/backup_and_recovery/RmanBlockCorruption.sql) - also check corruption
- [RmanBackupJobDetails.sql](https://github.com/karlarao/scripts/blob/master/backup_and_recovery/RmanBackupJobDetails.sql) - the backups
- [RmanMonitor.sql](https://github.com/karlarao/scripts/blob/master/backup_and_recovery/RmanMonitor.sql), [RmanMonitor2.sql](https://github.com/karlarao/scripts/blob/master/backup_and_recovery/RmanMonitor2.sql) - to check status of currently running RMAN backup