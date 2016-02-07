The __ihs__ cookbook uses IBM's Install Manager to install IBM HTTP Server. 

## Basic Use 

The __ihs__ cookbook only requires an IBM repository that contains IHS. The attribute [:ihs][:install][:repositoryLocation] __must__ be set to he location of your repository. 

If you do not know where to find a repository, you can start at this page: http://pic.dhe.ibm.com/infocenter/wasinfo/v8r5/index.jsp?topic=%2Fcom.ibm.websphere.installation.express.doc%2Fae%2Fcins_repositories.html


You may also need to set [:ihs][:install][:secureStorageFile] to the location of your secure storage file in order to access a repository, and if your secure storage file is password protected you will also need to point [:ihs][:install][:masterPasswordFile] to your master password file. 

This cookbook also supports keyfiles, however keyfiles are depreciated and we do not recommend their use. 
