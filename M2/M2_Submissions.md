<table><tr><td> <em>Assignment: </em> IT114 M2 Java-HW</td></tr>
<tr><td> <em>Student: </em> Brian Maina(bmm49)</td></tr>
<tr><td> <em>Generated: </em> 6/6/2022 10:59:53 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-m2-java-hw/grade/bmm49" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <p><br></p><p><strong>Template Files</strong>&nbsp;You can find all 3 template files in this gist:&nbsp;<a href="https://gist.github.com/MattToegel/fdd2b37fa79a06ace9dd259ac82728b6">https://gist.github.com/MattToegel/fdd2b37fa79a06ace9dd259ac82728b6</a>&nbsp;<br></p><p>Setup steps:</p><ol><li><code>git checkout main</code></li><li><code>git pull origin main</code></li><li><code>git checkout -b M2-Java-HW</code></li></ol><p>You'll have 3 problems to save for this assignment.</p><p>Each problem you're given a template&nbsp;<strong>Do not edit anything in the template except where the comments tell you to</strong>.</p><p>The templates are done in such a way to make it easier to capture the output in a screenshot.</p><p>You'll copy each template into their own separate .java files, immediately git add, git commit these files (you can do it together) so we can capture the difference/changes between the templates and your additions. This part is required for full credit.</p><p>HW steps:</p><ol><li>Open VS Code at the root of your repository folder</li><li>In VS Code create a new folder/directory called M2</li><li>Create 3 new files in this new M2 folder (Problem1.java, Problem2.java, Problem3.java)</li><li>Paste each template into their respective files</li><li><code>git add .</code></li><li><code>git commit -m "adding template baselines</code></li><li>Do the related work (you may do steps 8 and 9 as often as needed or you can do it all at once at the end)</li><li><code>git add .</code></li><li><code>git commit -m "completed hw"</code></li><li>When you're done push the branch<ol><li><code>git push origin M2-Java-HW</code></li></ol></li><li>Create the Pull Request with <b>main</b>&nbsp;as base and&nbsp;<strong>M2-Java-HW</strong>&nbsp;as compare (don't merge/close it yet)</li><li>Create a new file in the M2 folder in VS Code called m2_submission.md</li><li>Fill out the below deliverable items, save the submission, and copy to markdown</li><li>Paste the markdown into the m2_submission.md</li><li>add/commit/push the md file<ol><li><code>git add m2_submission.md</code></li><li><code>git commit -m "adding submission file"</code></li><li><code>git push origin M2-Java-HW</code></li></ol></li><li>Merge the pull request from step 11</li><li>On your local machine sync the changes<ol><li><code>git checkout main</code></li><li><code>git pull origin main</code></li></ol></li><li>Submit the link to the m2_submission.md file from the main branch to Canvas</li></ol><p><br></p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Problem 1 - Only output Odd values of the Array under "Odds output" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> 2 Screenshots: Clearly screenshot the output of Problem 1 showing the data and show the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172255980-84a488f7-465f-4a5b-82b2-97b26c3fd661.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code for Problem 1<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172256360-a00dd836-ca59-44a0-87fa-e42d5e30683a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The top portion of the output for Problem 1<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172256395-fdb41eed-34c8-4ea0-9d8b-e81eaeeeabb4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The bottom portion of the output for Problem 1<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>I used a for a loop. The for loop would go through each<br>index and see the index values is not divisible by 2 aka an<br>odd number. The for loop would then print out each odd number in<br>the array. This is repeated four times for the four Integer arrays<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Problem 2 - Only output the sum/total of the array values (the number must end in 2 decimal places, if it ends in 1 it must have a 0 at the end) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> 2 Screenshots: Clearly screenshot the output of Problem 2 showing the data and show the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172256542-4c19392a-e8b9-473b-93c7-0914abf3c945.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code portion of Problem 2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172256568-c5b4829b-5997-4aaf-8a9d-a19485e147b5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The output of Problem 2<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>I used a for statement and a double value called total. The for<br>loop would go through each index and add the value of the index<br>to the double value total. After the for loop is finished, the double<br>total value equals all the values added up from the double array. This<br>is repeated four times for the four Double arrays<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Problem 3 - Output the given values as positive under the "Positive Output" message (the data otherwise shouldn't change) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> 2 Screenshots: Clearly screenshot the output of Problem 3 showing the data and show the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172267066-4767a197-66ab-4edc-b712-459d2b1a878b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code for Problem 3<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/105742689/172267166-0cbc79e9-29ed-48a1-b6b1-5515b617d28c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output of Problem 3<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>I converted the T[] array to an object array. I then used an<br>Integer casting on the object array to be able to turn all the<br>negatives numbers in the Integers array positive<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc Items </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Pull Request URL for M2-Java-HW to main</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Crash105/IT114M2Java-HWPart3/pull/1">https://github.com/Crash105/IT114M2Java-HWPart3/pull/1</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Talk about what you learned, any issues you had, how you resolve them</td></tr>
<tr><td> <em>Response:</em> <p>I had issues with Problem 3. I, unfortunately, was only able to Integer<br>array positive conversion.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-m2-java-hw/grade/bmm49" target="_blank">Grading</a></td></tr></table>