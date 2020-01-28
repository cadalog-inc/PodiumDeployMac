to make the RBZ and OS installers:

* keeping in mind the version/year of Sketchup
** large HDR images make the rbz too big to sign
*** $ulf (use license file)

1. copy the content of Extras* from deploy into source
2. copy the content of extensions* from deploy into source
3. copy the small HDR images from deploy into source
4. zip the contents of source
5. rename the zip extension to rbz
6. sign on trimble
7. download the rbz file
8. rename the rbz extension to zip
9. unzip
10. copy the large HDR images from deploy into unzipped rbz over the small images**

to make the rbz installers:

11. set $ufl*** to false in SU_Podium_V26.rb
12. zip again
13. rename the zip extension to rbz
14. name with the build version and Sketchup year (SU_Podium_V26_043_2017.rbz)
15. upload to dropbox

to make the OS installers

11. set $ulf*** to true in SU_Podium_V26.rb
12. copy the contents of the unzipped rbz into the folder* in publish*
13. run the installer*
14. name the installer with the build version and Sketchup year
15. upload to dropbox

after finishing

16. remove the Extras, extensions and HDR content copied from deploy to source
17. repeat these steps for each version of Sketchup