# LMS_Live_Project
LMS stands for "Learning Management System", which is a website created by the Tech Academy for the purpose of teaching its students software development in an organized online structure. The Academy teaches several software related courses that are separated in different xml documents on the webpage. Each course has its own set of lessons, drills and links to different videos or documents. The product owner of the site wanted my team to develope code that would allow him to enter the title of each link right next to the actual link path itself. To do this he suggested that we use "magic strings".
The code I wrote here is designed to process the magic strings in each link in the xml documents. Here is an example of what a section of the xml would look like that would need to be processed.
       
       
        <q4>
          Watch these short code.org films:
          a.&lt;link&gt;%%%%%https://www.youtube.com/watch?v=m2Ux2PnJe6E#####^^^^^Bill Gates Explains If Statements. (1:46)$$$$$&lt;/link&gt;
          b.&lt;link&gt;%%%%%https://www.youtube.com/watch?v=mgooqyWMTxk#####^^^^^Mark Zuckerburg Teaches Repeat Loops. (1:34)$$$$$&lt;/link&gt;
          c.&lt;link&gt;%%%%%https://www.youtube.com/watch?v=G2hdlhDYICw#####^^^^^Chris Bosh Teaches Repeat Until Statements. (0:51)$$$$$&lt;/link&gt;
          d.&lt;link&gt;%%%%%https://www.youtube.com/watch?v=JtL7w6ja5iI&amp;index=5&amp;list=PLzdnOPI1iJNemVBckyuo_m97bFF2hbL9J#####^^^^^Saloni on the If/Else Block. (0:42)$$$$$&lt;/link&gt;      
        </q4>
