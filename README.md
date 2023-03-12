Simple script to move anything that was last modified from 30+ days to one location the next.
Set the source and destination folders:
- $sourceFolder = '\\Server1\SharedFolder' $destinationFolder = '\\Server2\ArchiveFolder'
If want to edit it for more days edit the 30 to the desired number:
- (Get-Date).AddDays(-30)
