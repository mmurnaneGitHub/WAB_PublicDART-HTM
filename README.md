# WAB_PublicDART-HTM
Method for allowing htm page to run Esri Web AppBuilder.

TacomaPermitsMap.htm:

A. Duplicate index.html as TacomaPermitsMap.htm.

B. Modify env.js (//MJM) to allow *.htm - add below line ~202 in function getPath() - /\.htm$/.test(lastSection) ||

Version 2.14
