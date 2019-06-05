# Gzip-Server

This example shows a simple file server that accepts a gzipped file from a client,it decompresses it and stores it inside the current folder.

To run the server you need to launch:

```bash
node gzipReceive
```

Then, you can send any file with:

```bash
node gzipSend <pathOfTheFileToSend> localhost
```
