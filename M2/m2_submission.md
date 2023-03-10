<table><tr><td> <em>Assignment: </em> IT114 M2 Java-HW</td></tr>
<tr><td> <em>Student: </em> Michael Kiss (mbk28)</td></tr>
<tr><td> <em>Generated: </em> 2/21/2023 10:27:33 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-008-S23/it114-m2-java-hw/grade/mbk28" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <p><br></p><p><strong>Template Files</strong>&nbsp;You can find all 3 template files in this gist:&nbsp;<a href="https://gist.github.com/MattToegel/fdd2b37fa79a06ace9dd259ac82728b6">https://gist.github.com/MattToegel/fdd2b37fa79a06ace9dd259ac82728b6</a>&nbsp;<br></p><p>Setup steps:</p><ol><li><code>git checkout main</code></li><li><code>git pull origin main</code></li><li><code>git checkout -b M2-Java-HW</code></li></ol><p>You'll have 3 problems to save for this assignment.</p><p>Each problem you're given a template&nbsp;<strong>Do not edit anything in the template except where the comments tell you to</strong>.</p><p>The templates are done in such a way to make it easier to capture the output in a screenshot.</p><p>You'll copy each template into their own separate .java files, immediately git add, git commit these files (you can do it together) so we can capture the difference/changes between the templates and your additions. This part is required for full credit.</p><p>HW steps:</p><ol><li>Open VS Code at the root of your repository folder</li><li>In VS Code create a new folder/directory called M2</li><li>Create 3 new files in this new M2 folder (Problem1.java, Problem2.java, Problem3.java)</li><li>Paste each template into their respective files</li><li><code>git add .</code></li><li><code>git commit -m "adding template baselines</code></li><li>Do the related work (you may do steps 8 and 9 as often as needed or you can do it all at once at the end)</li><li><code>git add .</code></li><li><code>git commit -m "completed hw"</code></li><li>When you're done push the branch<ol><li><code>git push origin M2-Java-HW</code></li></ol></li><li>Create the Pull Request with <b>main</b>&nbsp;as base and&nbsp;<strong>M2-Java-HW</strong>&nbsp;as compare (don't merge/close it yet)</li><li>Create a new file in the M2 folder in VS Code called m2_submission.md</li><li>Fill out the below deliverable items, save the submission, and copy to markdown</li><li>Paste the markdown into the m2_submission.md</li><li>add/commit/push the md file<ol><li><code>git add m2_submission.md</code></li><li><code>git commit -m "adding submission file"</code></li><li><code>git push origin M2-Java-HW</code></li></ol></li><li>Merge the pull request from step 11</li><li>On your local machine sync the changes<ol><li><code>git checkout main</code></li><li><code>git pull origin main</code></li></ol></li><li>Submit the link to the m2_submission.md file from the main branch to Canvas</li></ol><p><br></p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Problem 1 - Only output Odd values of the Array under "Odds output" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> 2 Screenshots: Clearly screenshot the output of Problem 1 showing the data and show the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98507798/216840318-5070edd9-6e16-49f1-b31e-5d763bff1b72.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing output. <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98507798/220513608-060b42a1-4961-49ee-9e16-716eeeb4b8f8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>If loops through each indices of the array and divides it by two.<br>If the value left over is not equal to zero when divided by<br>two it will print out that odd value. Nothing needs to be returned<br>since it is a static method.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Problem 2 - Only output the sum/total of the array values (the number must end in 2 decimal places, if it ends in 1 it must have a 0 at the end) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> 2 Screenshots: Clearly screenshot the output of Problem 2 showing the data and show the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98507798/216841031-0aee7268-d0a7-440f-a352-f4d042dacabe.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing output. <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98507798/220513704-d039d4af-58ee-4b09-b391-19d9f54aa34d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>Totaling logic was looping through the array and calculating a running total of<br>each index to the already declared variable total.&nbsp;<div><br></div><div>The rounding was using the math.round()<br>to the total integer each time the function loops through. By multiplying and<br>dividing by 100.0 it cuts off the rest of the decimals, but keeps<br>the value the same. Whereas if I did it before adding.&nbsp;</div><div><br></div><div><br></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Problem 3 - Output the given values as positive under the "Positive Output" message (the data otherwise shouldn't change) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> 2 Screenshots: Clearly screenshot the output of Problem 3 showing the data and show the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98507798/216841386-5bdf7966-4339-448b-8442-b11f41ebc642.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing output. <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98507798/220513776-59291b9d-cd6e-4692-bf1a-22fb32b2b1a4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p><b>Positive conversation&nbsp;was done by using the java.math.abs to find the absolute value which<br>would convert negative values to positive.&nbsp;</b><div><b><br></b></div><div><b>The conversion/casting was done by using if statements<br>and &quot;instanceof&quot; to see which primitive type the index was, or if it<br>was a string. Then some if statements&nbsp;to see how it should handle that<br>data. For the doubles and ints it was simple math.abs. For the strings<br>we needed to parse it for the integer value. After that we just<br>needed to assign it to the same index on the output[] array.&nbsp;</b></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc Items </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Pull Request URL for M2-Java-HW to main</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/mkiss28/IT114-008/pull/3">https://github.com/mkiss28/IT114-008/pull/3</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Talk about what you learned, any issues you had, how you resolve them</td></tr>
<tr><td> <em>Response:</em> <p>I learned how to handle different data types. Had alot of issues with<br>handling the String values, because I tried alot to use CharAt 0 .equals<br>&quot;-&quot; and creating a substring, but it wasn&#39;t working because this is an<br>object data type. Eventually just settled on handling it like an int, and<br>that is more functional anyway if I got an arraylist with multiple different<br>datatypes.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-008-S23/it114-m2-java-hw/grade/mbk28" target="_blank">Grading</a></td></tr></table>
