# MAPLE Package
Maple package files from [Frank G. Garvan](http://www.qseries.org/fgarvan/research.html).



If you want to install packages easily, just copy the .m or .mla file located in [Package](https://github.com/tarregahong/Maple_Package/tree/master/Package) into your Maple library. Using qseries.m for instance, my Maple is installed to D:\Program Files\Maple 18. There is a folder named "lib". After copying qseries.m to this folder, restart Maple and we can use "with(qseries)" in Maple to test whether we have added the package successfully.



If you want to build packages from Gavan's source code, you can follow the brief guide. Again, we use [ q-series](http://qseries.org/fgarvan/qmaple/qseries/index.html) package as an example:

1. Download the source code [here](http://qseries.org/fgarvan/qmaple/qseries/wprog-qseries-08-12-2016-HOMEPC.txt). This is a .txt file, you can put it in any folder and use any name you like, here, say, “C:\download\”. Filename has been change to "qseries.txt".
2. Open the .txt file and scroll down to the last 4 lines, then you can find a line as "c:\\cygwin64/home/fgarvan/maple/mylib/qseries.mla"). Change this to your Maple address and save. Here for me, is "d:\\Program Files/Maple 18/lib/qseries.mla". Don't use wrong symbols for "\\" and "/".
3. Create a new document in Maple and use command "currentdir("c:\\\download\\\\")" (no outside quotation marks). The address here must be same as the one in step 1. IMPORTANT, here must two "\\".
4. Run command "read "qseries.txt";". Here the name should be same as step 1.
5. Restart Maple and use "with(qseries)" to check the package.



For Mac OS user, just replace all the address above to corresponding address in Mac OS. Other steps are exactly same. 

