# Disk Wiper

This script securely overwrites a specified block device (e.g., hard drive, SSD) by writing either random data or zeroed data to it multiple times. It uses the `dd` utility to perform the overwrite operation and ensures that the data is written to disk by syncing the writes.

>[!WARNING] 
This script will **permanently erase all data** on the specified disk. **Use with extreme caution**. The script is provided as-is, and you run it at your own risk.

## Requirements

- Linux-based system (works on most distributions).
- `dd` utility installed (usually included by default on most Linux systems).
- Root (administrator) privileges to access and overwrite block devices.

## Important Disclaimer

By using this script, you acknowledge the following:

- **You are solely responsible** for any data loss, damage, or other consequences that result from running this script.
- **All data on the specified disk will be permanently erased**. This process is irreversible. Ensure that you have backups of any important data before proceeding.
- The script will not check for specific file system types, partitions, or other potential issues that may arise during execution.
- The script does not provide any guarantees, and it is offered "as-is". You assume all risks associated with its use.
- **It is your responsibility to verify the disk** that you wish to overwrite. The script will not prevent you from overwriting critical system disks or partitions.
- If you use this script, you understand and agree that the author and any related parties are not liable for any damage, data loss, or other issues that may occur.
- Use it at your own risk, and please read and understand the above disclaimer before proceeding.
