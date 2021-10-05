SharePoint HTTP Request to BreakInherit Permission for a List Item / Folder / File. 

Request Type : POST
Request URI  : _api/lists/getByTitle('<Lib/List tile>')/items('<Item-ID>')/breakroleinheritance(copyRoleAssignments=false,clearSubscopes=true)
Example      : _api/lists/getByTitle('Documents')/items(61)/breakroleinheritance(copyRoleAssignments=false,clearSubscopes=true)


Revert Back BreakInherit Permission for a List Item / Folder / File. 

Request Type : POST
Request URI  : /_api/Web/Lists/GetByTitle('<Lib/List tile>')/items('<Item-ID>')/resetroleinheritance
Example      : _api/Web/Lists/GetByTitle('Documents')/items('61')/resetroleinheritance
