This function app destroys all resource groups that have the tag 'DestructionTime' at the time specified by the tag's value.  Value must be readable as input into `Get-Date`.  Destruction will take place on the hour every hour between 5pm and midnight.