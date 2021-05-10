# Linkedinlearning-downloader
Downloading Linkedin learning videos directly into your Google drive

This is the project implementation on online through **Google Colab** based on [python linkedin learning video downloader project](https://pypi.org/project/llvd/).

⚠️⚠️⚠️To download Linkedin learning course videos You need active subscription on linkedin learning platform.You can get one month free trail on linkedin register your free trail and then try this script to download your course videos.

To get started with linkedin video downloader Get into this [Google colab link](https://colab.research.google.com/github/LAVANSURESH/Linkedinlearning-downloader/blob/main/Linkedin-learning-video(course)%20downloader.ipynb)  and Mount your google drive and give the needed details to download the course into your google drive. 


Tool Features:

      ✅cookie-based authentication
      ✅download a course and all its exercises
      ✅group videos by chapters
      ✅subtitles
      ✅Nice progress bar
      ✅resume failed downloads
      ✅skip already downloaded videos
      ✅set video format (360p, 540p, 720p)
      ✅Internet speed:100kbps (In google colab to download full course and automatically save it in your drive) 
      ✅You can save this files in your shareddrive also.
      ✅No piracy promoted here Use this tool for your own purpose.


Step 1:**Run the first shell to mount your google drive in google colab.**

![linkedin course github](https://user-images.githubusercontent.com/64597701/117582341-336fce80-b11f-11eb-8cc5-826352260303.png)

Step 2:**Output directery:**
        
 ![COPYPATH](https://user-images.githubusercontent.com/64597701/117605274-fb937600-b174-11eb-9035-74476bce6025.png)
         
         -->Right click the directory where you want the save video courses.
         -->Copy the path and paste in output_dir field
         
         
   
 ![image](https://user-images.githubusercontent.com/64597701/117605505-7c527200-b175-11eb-861f-549f428af120.png)


Step 3:**Getting course slug**

   Eg1:
                 
                 COURSE URL: https://www.linkedin.com/learning/learning-autodesk-inventor/creating-a-base-extrusion
                 SLUG: learning-autodesk-inventor

![image](https://user-images.githubusercontent.com/64597701/117606048-b112f900-b176-11eb-8efc-3fb37811ccb7.png)
                 
                 The highlighted text in the url is course slug to download course
                 
Step 3:Getting validate cookies for your account through developer tools in chrome:

              -->Login into your linkedin learning account.
              -->Click on the options in the google chrome (top right with 3 vertical dots).
              -->After this, click on more tools followed by Developer Tools (you can also reach here by using the keyboard combination — ctrl+shift+I).
              -->Now once you’ve gained access to the developer tools, navigate to the Application tab, and copy the value of two cookies from there named li_at and JSESSIONID respectively.
              -->Once you got the credintials Just enter that credintials into the required field.
              
![image](https://user-images.githubusercontent.com/64597701/117606202-00592980-b177-11eb-99c0-df070b0d9fa5.png)

              -->This is the developer tab screenshot.Just get into application tab and enter into cookies to get credintials.
              
![image](https://user-images.githubusercontent.com/64597701/117606411-6f368280-b177-11eb-9589-6743cc897706.png)

              -->Enter your credintials in respective fields.
              
Enter the quality:360p,540p,720p

**And run the shell It will download the needed dependencies and install it.And starts download your required course in your output directory.**


**⚠️⚠️⚠️Developer not responsible for any illegal use.No piracy.Use this tool for personal use.**
