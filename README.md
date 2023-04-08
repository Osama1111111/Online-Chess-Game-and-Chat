# Online-Chess-Game-and-Chat

## ♟ Chess game <a name = "unit"></a>
An assembly program where you can play online chess game with inline chatting or to go to chat room directly.
*	Press f1 to go to the chatting room.
* Press f2 to go to the chess game:<br />
This game has some different rules than the traditional chess. Every player could move any piece without turns, but the moved piece have to be frozen for 3 seconds to be able to move again.<br /><br />
You can read the description for more details 
<!-- <p align="center">
    <img width=800px height=410px src="https://github.com/aashrafh/CMP201A/blob/master/Execution%20Unit/test/TestCaseAfterOrg1.PNG" alt="ExecutionUnitDeom">
  <img width=800px height=410px src="https://github.com/aashrafh/CMP201A/blob/master/Execution%20Unit/test/Test2.PNG" alt="ExecutionUnitDeom">
 </p> -->

## 🏁 Install <a name = "Install"></a>
1. Install [DOSBox](https://www.dosbox.com/).
2. Open ```DOSBox Options```.
3. Add the following lines to the end of the text file.
```
mount c Z:\Workspaces\FolderName
c:
masm fileName.asm;
link fileName.obj;
fileName
```
**Note:** do not forget to replace ```Z:\Workspaces\FolderName``` with your local directory.

## ⛏️ Built Using <a name = "tech"></a>
- [Assembly8086](https://en.wikipedia.org/wiki/X86_assembly_language) - low level programming language.
- [DOSBox](https://www.dosbox.com/) - emulator program.
