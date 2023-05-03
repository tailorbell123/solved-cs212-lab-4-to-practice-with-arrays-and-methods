Download Link: https://assignmentchef.com/product/solved-cs212-lab-4-to-practice-with-arrays-and-methods
<br>
5/5 - (1 vote)

To practice with arrays and methods.

<ol>

 <li>Download the application Lab4Program1.java from the folder for Lab 4 on Blackboard (it may also be available on the public drive of the lab machines in the directory Spring2009.) Open the program with the editor of your choice and observe the following:Two statements from the JOptionPane class take care of the input and output of Strings.JOptionPane.showInputDialog(null, String) opens an input window containing the message in the String parameter. The user may enter any String, and click OK. The method returns the String.JOptionPane.showMessageDialog(null, String) simply displays the String as a message in a window and waits for the user to click OK.Compile and run the program.</li>

 <li>Note that no matter what word you type into the input dialog, the program always answers that the word is not on the list, because the method wordIsThere simply returns false.Rewrite the method wordIsThere so that it searches the array for the given word and returns true only if the word is on the list. Remember that you cannot compare Strings with the “==” operator. You must use the equals method of class String, for example:if(s1.equals(s2)) will compare String s1 with String s2</li>

</ol>

Compile and run the program.