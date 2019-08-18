# tags-company
 
 use tags more flexible for company.

 by default, to use this package you need to update the ctag to
 universal-ctags. otherwise, you need to fix the commad in
 tags-company/create-tags-command-and-option variable.

 create tags-company/conf file to directory as root directory.
 and create tags use tags-company/update. the TAGS file will be
 created at root directory. when use tags file to company. it will
 use of just ceated TAGS file.

 you can add more then one TAGS file to add path to the tags-company/conf
 files.

 you can toggle the way when save buffer automatically re-create tags.
 use of the tags-company/toggle-update-tags-when-save-buffer function.

 tags-company/update-all-tags controll the create tags way.
 if nil (for default) just re-create root directory's tags.
 if t, re-create all tags that the tags-table-list paths.

 tags-company/conf variable the conf file.

 all function available function and variable is started prefix tags-company.

 all issue is welcome. like nicolas4d is very handsome! 
