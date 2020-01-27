to make the RBZ and OS installers:
* keeping in mind the version/year of Sketchup
** large HDR images make the rbz too big to sign

1. copy the content of Extras* from deploy into source
2. copy the content of extensions* from deploy into source
3. copy the small HDR images from deploy into source
4. zip the contents of source
5. rename the zip extension to rbz
6. sign on trimble
7. download the rbz file
8. rename the rbz extension to zip
9. unzip
10. copy the large HDR images from deploy into source over the small images**

to make the rbz installers:

11. zip again
12. rename the zip extension to rbz
13. name with the build version and Sketchup year (SU_Podium_V26_043_2017.rbz)
14. upload to dropbox
15. remove the Extras, extensions and HDR content copied from deploy to source
16. repeat these steps for each version of Sketchup

to make the OS installers

11. copy the contents of the unzipped rbz into the packages folder in publish*
12. run the installer*
13. name the installer with the build version and Sketchup year
14. upload to dropbox
15. remove the Extras, extensions and HDR content copied from deploy to source
16. repeat these steps for each version of Sketchup