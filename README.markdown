requires OpenCV and CvBlob to run

##TODO

###BLOB TRACKER
- ckeck collision between current blobs and list of active blobs
 - if blob from active blobs is not colliding with any current blob remove from active blobs list
 - if blob from current blobs is not colliding with any active blobs:
  - add to active blobs list with new ID
  - flag blob for polling
 - if blob from active blobs is colliding replace active blob with current blob
 - if current blob is colliding with more than one active blob:
  - players must be convoluted
  - assign current blobs atributes to all active blobs it's colliding with
  - flag all active blobs for polling