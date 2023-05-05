accept the pull request !!

1)new repository for SODA Strato

Issue/Feature Description:

Create a new repository for SODA Strato UI using the current code base of the SODA Dashboard and remove all the code that is not required for the SODA Strato (Terra, Delfin and Orchestration.)

Why this issue to fixed / feature is needed(give scenarios or use cases):

Going forward we will have individual dashboards for all the SODA Foundation framework projects.
These dashboards will be hosted in different repositories and will be released along with the project release.

How to reproduce, in case of a bug:

Other Notes / Environment Information: (Please give the env information, log link or any useful information for this issue)

2)Test SODACODE Test Issue

Issue/Feature Description:

bug on xxxx

Why this issue to fixed / feature is needed(give scenarios or use cases):

needs to fix yyy

How to reproduce, in case of a bug:

steps abc, edc,

Other Notes / Environment Information: (Please give the env information, log link or any useful information for this issue)
NA




3)Analyze how to access the metada of externally orchestrated S3 buckets

Issue/Feature Description:

Analyze how to access the metada of externally orchestrated S3 buckets:

 The scope of this task is to analyse accessing of s3 bucktes. Which all parameters/steps required.
 Any challange accessing different types of buckets from different region of different storage class etc.
 For AWS cloud
 For GCP cloud
 
Why this issue to fixed / feature is needed(give scenarios or use cases):

How to reproduce, in case of a bug:

**Other Notes **

 Please prepare the google doc for this analysis




4)Analyze all metadata of externally orchestrated S3 buckets using CLI

Issue/Feature Description:


Analyse metadata of externally orchestrated S3 buckets using CLI:

 The scope of this task is to analyse all metadata of s3 buckets.
 How can we aquire these metadata
 For AWS cloud
 For GCP cloud
 
Why this issue to fixed / feature is needed(give scenarios or use cases):

How to reproduce, in case of a bug:

**Other Notes

 Please prepare google doc for this task
 
 
 
 
 
 
 
5)Create the new SODA Experience dashboard scaffolding with basic code structure and basic dependencies

Issue/Feature Description:
This is for the new SODA Experience Dashboard which will provide the users an easy way to access the following for any project that is integrated into the dashboard:

Project Description
Use Cases & Features
Architecture Diagram
Link to User Guides
Link to Developer Guides
Video Demos
Link to project Dashboard
Install project

Why this issue to fixed / feature is needed(give scenarios or use cases):
The current SODA dashboard was developed as a demo client for the OpenSDS projects( SODA Terra and Strato projects )
With new projects being added to the SODA Framework and to make it easier for users who install or want to install SODA projects the SODA Experience will provide a single window for new users to get onboard quickly.

How to reproduce, in case of a bug:

Other Notes / Environment Information: (Please give the env information, log link or any useful information for this issue)


6)Dashboard does not redirect to login screen even after the session is timed out

Issue/Feature Description:

If the SODA Dashboard is left idle for a while, the authentication token gets expired in the keystone backend but the dashboard does not reflect the same. It remains active and allows user to perform actions for ex: create bucket, create profile etc.
On clicking the create button the API throws a 403 unauthorised error due to the token not being valid.

Why this issue to fixed / feature is needed(give scenarios or use cases):
Users should not be allowed to perform any actions if the session token is timed out. They should be logged out and prompted to login again.

How to reproduce, in case of a bug:

Login to the dashboard.
Leave it idle for 30 minutes or so
Try to register a backend or create a bucket.

Other Notes / Environment Information: (Please give the env information, log link or any useful information for this issue)
This issue is observed in #294 where more details can be seen.
Similar feature is requested in #570.
