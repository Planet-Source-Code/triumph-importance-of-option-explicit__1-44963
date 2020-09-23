<div align="center">

## Importance of Option Explicit


</div>

### Description

So many people (especially beginners) do not realize the importance of the simple statement Option Explicit in their code. Find out why it is so important.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Triumph](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/triumph.md)
**Level**          |Beginner
**User Rating**    |4.9 (64 globes from 13 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/triumph-importance-of-option-explicit__1-44963/archive/master.zip)





### Source Code

<DIV>
<DIV align=center><STRONG><FONT size=5>The Importance of Using Option Explicit</FONT></STRONG></DIV>
<P></P>
<P><BR>Many programmers (especially new ones) neglect the use of the <FONT face=Courier>Option Explicit</FONT> statement in their programs. THIS IS <STRONG>VERY</STRONG> BAD CODING!!! I have seen many programs not run at all, much less properly because of not having this simple statement. As a matter of fact, Visual Basic makes it simple to include this sttement in all of the programs you write. Go to <FONT face=system>Tools > Options > Editor (tab) > "Require Variable Declaration"</FONT><FONT face=Arial>. Check it. It does not appear in the program you have running, but the next new one you open will have it.</FONT></P>
<P>"Why is it so important to include this?" you ask. Well, there are many reasons.<BR><BR><STRONG>1. It stops you from making costly errors.</STRONG><BR></P></DIV>
<P>Without <FONT face=Courier>Option Explicit</FONT>, if you spell a variable wrong in a procedure, Visual Basic will think you are trying to create a new vairable and will create one for you. Then, if you try to read that same variable later on (this time spelling it correctly) it will not have the desired value.</P>
<P><STRONG>2. It is good coding practice.</STRONG></P>
<P>I know a man who interviews programmers, and the first question he asks in the interview is, "What is <FONT face=courier>Option Explicit</FONT>?" If they don't know or answer incorrectly, they are not hired. Then, he asks them when they use it, and, usually, if the answer is not "always", they don't get the job. <FONT face=courier>Option Explicit </FONT><FONT face=Arial>is <EM>extremely</EM> important when working with other people. Making a spelling error in your code, which you know because you wrote, may be easy to find. But, if someone else, who does not know your code so well, tries to find it, it could take hours.</FONT>
<P> </P><BR><FONT size=3>Overall, using <FONT face=Courier>Option Explicit</FONT> is a good idea, and saves you time and sanity. I know this was not a long drawn out tutorial, but so many people do not use it, and it is so important that they do.</FONT>

