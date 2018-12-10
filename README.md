# DocuSimple file-manager

The file-manager is responsible for interacting with the file storage backend. Keeping this a separate component makes it easier to implement interfaces for interacting with different types of file storage. This could be local filesystem, S3, FTP, etc.

file-manager exposes an API which will allow meta-manager to query and make simple updates (such as renaming a file), and well as allow the mobile or web app to retrieve a file, whether directly or by proxy.
