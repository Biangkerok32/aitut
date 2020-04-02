Source https://community.appinventor.mit.edu/t/how-to-read-asset-file/6030/4

InputStream in = null;
try {
  in = container.$form().openAsset(path);
} finally {
  IOUtils.closeQuietly(in);
}
