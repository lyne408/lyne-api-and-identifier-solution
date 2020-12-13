
## Path relative

- getFileName
	getFileNameWithoutExtension

- getFullFileName
	getFileNameWithExtension
	
- getParentName
	getParentDirectoryName
	getParentFolderName
	
- getDirectoryName
	getFolderName

- filenameContainsOf
	filenameIncludesOf
	
- extnameOf

- safenPath

- safenFileName

- replaceExtname


## File System Relative

- isExist

- isFile

- isDirectory

- isEmptyDirectory

- createDirectory

- createFile

- deleteFile

- deleteDirectory

- getFileNameOfURL

- getMD5FromBuffer

- renameForBackup

- filterFilesAndDirectories
	file 仅表示文件, directory 仅表示目录
	可能同时有文件和目录, 用 filesAndDirectories
	
- filterFiles
	只筛选文件
	
- filterDirectories

- getSubfiles

- getSubdirectories

- reserveSmallerFiles

- writeArrayToFile