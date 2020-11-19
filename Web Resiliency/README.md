# Web Resiliency on AWS
Recoverying from acidential deletion or change of item from database is the the goal of Web Resiliency

## 1. The original file was uploaded at 11:43 
![Original File upload at 11:43](https://github.com/eedygreen/Recoverability-In-AWS/blob/master/Web%20Resiliency/s3_original.png)
<br> <br/>

## 2. The background photo was changed to a different background at 11:50 
![New File uploaded at 11:50](https://github.com/eedygreen/Recoverability-In-AWS/blob/master/Web%20Resiliency/s3_season.png)
<br> <br/>

## 3. The Reverted File - The replaced file was reverted at 11:55 
![Reverted File at 11:55](https://github.com/eedygreen/Recoverability-In-AWS/blob/master/Web%20Resiliency/s3_season_revert.png)
<br> <br/>

## 4. The Deleted File - The file was deleted at 12:25 
![File Deleted at 12:25](https://github.com/eedygreen/Recoverability-In-AWS/blob/master/Web%20Resiliency/s3_deletion.png)
<br> <br/>

## 5. The Deletetion Marker from S3 showing the file has been deleted
![Deletion Marker at 12:25](https://github.com/eedygreen/Recoverability-In-AWS/blob/master/Web%20Resiliency/s3_deletion_marker.png)
<br> <br/>

## 6. The Reverted Delete File - the file was reverted at 12:33
![Reverted Delete File at 12:33](https://github.com/eedygreen/Recoverability-In-AWS/blob/master/Web%20Resiliency/s3_deletion_revert.png)


## Summary
**The Web Resiliency on AWS with static page website hosted on S3. The background photo on the website was constantly changing and deleted, but it was recovered from these changes wihtout uploading the same file. The Resiliency shows how S3 handles fault tolerance to data stored as blob storage and how it can be relied upon.** https://github.com/eedygreen/Recoverability-In-AWS
