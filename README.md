Script sets a source folder and a destination folder, and then retrieves a list of files from the source folder that were last modified more than 30 days ago. Then it loops through the list of files and moves them to the destination folder.

Set the source and destination folders:
- $sourceFolder = '\\Server1\SharedFolder' $destinationFolder = '\\Server2\ArchiveFolder'
If want to edit it for more days edit the 30 to the desired number:
- (Get-Date).AddDays(-30)
