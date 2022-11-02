# How to host and format a resume
 
## Purpose: 
Describe the practical steps of how to host and format a resume. 

## Prerequisites: 
Prepare your laptop, internet connection, your resume(written in markdown format), and your github account. If you don't know about what is a github, it is a distributed version control system(DVCS) which is commonly used nowdays. It is useful for concurrent work on same task.
 
## Instructions: 
How to host your resume on github page using Jekyll
   
  #### Download Jekyll
   
   1. Download [Ruby](https://jekyllrb.com/docs/installation/macos/)
   2. Download [Jekyll](https://jekyllrb.com)
   
  #### Create a repository on [github](https://github.com)
   
   1. Click the **Create** button on your repository page.
   2. Name the repository as username.github.io
   
  #### Create _config.yml file
  
   1. Click **Add File** > **Create** new file on the top right corner
   2. Name the title _config.yml
   3. Write two lines of code (You may choose different themes from this example)
    
   ```
   title: Your Title
   theme: jekyll-theme-minimal
   ```
   4. Click the **Commit new file** button at the bottom
   
  #### Upload your resume
  
   1. Click the **Add file** button
   2. Click **Create new file** or **Upload file**
   3. * Create new file: When you are creating a new file, name the file 'index.md'. For the content, write your resume in markdown format which is lightweight markup.
      * Upload file: Upload your existing resume file written in markdown format from your computer.
   4. And click **Commit changes**.
   
  #### Check your resume
   
   1. Go to the website 'username.github.io'
   2. You can see your resume!

   ![GIF](https://github.com/gyuyuu/gyuyuu.github.io/blob/main/resume.GIF)

  #### More Resources:  
   
   1. [Markdown tutorial](https://www.markdowntutorial.com)
   2. [Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
   3. [Useful template](https://github.com/murraco/jekyll-theme-minimal-resume)
 
## Authors and Acknowledgments: 
 * Author: Gyuri Kim
 * Acknowledgement: Template theme by [orderedlist](https://github.com/orderedlist)
 * Group members: Thanks to Ahir Zaman, Yun Ji How, and Dharmit Anghan for reviewing my README.md file and index.md file.

## FAQs:

   1. Why is Markdown better than a word processor?: Markdown is simple and easier to use than a word processor. Also it can easily write source codes.
   2. Why is my resume not showing up?: When you are hosting your github page for the first time, you maybe should wait for several minutes until it compeletely be processed. If it still not showing up, then check your repository title. It should be your username.github.io.
 
