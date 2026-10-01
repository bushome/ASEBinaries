So, since Studio Sirens is at present off project working on SOTF for ASA thought as an experiment to see if performance could be improved by updating some of the deployment files for their respective tool kit versions to help in some areas. Granted, replacing them will NOT fix some of the obvious bugs....(cough, like the mech spawner, cough ) but if it's a bug pertaining to a library version in an older file....then maybe it will help. We can't expect much at this point. So drop these in your win64 folder and see if it helps. ( goes without saying, always make a backup beforehand )

I'll be updating the steam client files, Epic Game Services from the SDK, and a few of the visual basic files in this archive as needed. The rest are considered version locked beyond what I've put together to be compatible for running ASE for the most part so those will not be touched beyond what is posted. 

I've tested launching the dedicated server software and client to make sure they run with these on my server box and workstation. Server launched and loaded, same with the client logging into the game. I do the same with my ASA servers and client playing on a regular basis so it's not something I haven't done before. 

Running Win11 on both machines as the production environment.

Running Win11 on both machines as the production environment.

Direct X APIs v. 10.0.26100.6584 ( yeah i'm not listing all of these...too dang many and they are all the same version )
d3d9.dll 10.0.26100.6725
msvcp110.dll 11.0.65501.17010
msvcp120.dll 12.0.40664.0
msvcr110.dll 12.0.30501.0
msvcr120.dll 12.0.40664.0
ssleay32.dll 2.6.46.11
libeay32.dll 1.4.5.0
ucrtbase.dll 10.0.28000.1
vstdlib_s64.dll 10.68.89.93
xaudio2_9redist.dll 1.0.2504.10003
--------------------------------------
Files below will be updated as new releases become available......date stamp will be the last updated day and most recent available on that date.

EOSSDK-Win64-Shipping.dll
concrt140.dll
vcruntime140_1.dll
vccorlib140.dll
vcruntime140.dll
msdia140.dll
msvcp140.dll
msvcp140_1.dll
msvcp140_2.dll
steamclient.dll
steamclient64.dll
tier0_s64.dll
