**Contains the latest community maintained Sonic Heroes disassembly.**

-------------

- **Format**: IDC (Interactive Disassembler Script/IDA)

- **Prerequisites**: Sonic Heroes executable (w/o DRM | Sonic PC Collection/CFB/Reloaded)

**Why IDC?**
- We would like to make the disassembly easily available; across both legitimate IDA users, free users, and the others; as well as across versions.

- IDC is text based and allows for partial diffing support. This means that while due to the automated exporting process, merge requests may still prove very difficult to do so; they will at least not be impossible.

- We do not want to ship a complete binary copy of the original game's executable! (Even if an IDB would have it inside its container)

**Usage**

To use the IDC file, create a new clean disassembly by opening the game executable inside IDA.

Once the initial analysis completes (you will be thrown into graph view), navigate to File => Script File and select the IDC.

**Contributing**

To contribute, navigate to File => Produce File => Dump Database to IDC File.

After you are done, replace the original IDC in the git repository and pray that you wouldn't have to go through merge conflicts in the case someone else worked on the disassembly at the same time as you.

Due to the difficulties of merge conflicts, it is **HIGHLY RECOMMENDED** that you commit often; preferably after every session - even if all you did was label 2-5 elements.

**Disclaimer**

Any and all content presented in this repository is presented for informational and educational purposes only. Commercial usage is expressly prohibited. Heroes Hacking Central claims no ownership of any code in these repositories. You assume any and all responsibility for using this content responsibly. Heroes Hacking Central claims no responsibiliy or warranty.
