# Target Audience Analysis
### Task Description📜
Currently we are facing a lack of Customers and Audience on our LinkedIn  Page. The goal of this task is to get as many people as we can so that we can attract them from our posts and sell them our services to generate revenue. With LinkedIn scraping, we'll be able to collect a data pool of people with their details, where we can identify who can become our Target Audience.
We’ll use the profile URLs of likers and commenters, for scraping profile data like (Name, Title, Followers, Connection, Experience, Curren/Last Designation, Certifications, Skills, and Education) by using the profile scraper code. Make a copy of this profile data, and store this data along with the posts.
With this invaluable data at our fingertips, We’ll categorize the profiles into 8-10 different categories on the basis of the Skills column. Our mission is to uncover potential clients!
Once we've revealed the secrets, we'll get an idea of which kind of audiences are mostly attracted to which kind of posts, so that we can customize our future posts according to this information.
Together, we will unlock the full potential of LinkedIn and elevate Ozigen's online presence to new heights!

[Go to the notion page for detail understanding of the task↗️](https://docs.google.com/document/d/1lpqrSfYIm4M5RGakFS-gzObmP9jVybTxDKrgsuAAelc/edit#heading=h.vcqhms74oo6)


### Task Objective🎯
The Objective task is to get an idea of which kind of audiences are mostly attracted to which kind of posts (on the basis of theme) so that we can customize our future posts according to this information.

### 📁File Details
#### 1. Modified_LinkedIN_Profile_Scrapper Code
 - This code performs the web scrapping of LinkedIn profiles.
 - [Go to File↗️](https://github.com/ozibook/Target_Audience_Analysis/blob/main/Modified_Linkedin_Profile_Scraper_byAvinaba.ipynb)
#### 2. No_likes_comments_repost_caption Code
 - This code gives the caption, number of likes, comments of the posts when provided with the **links** of the posts as a **list**.
 - [Go to File↗️](https://github.com/ozibook/Target_Audience_Analysis/blob/main/No_likes_comments_repost_caption.ipynb)
#### 3. Updated_Commenters_Scraping Code
 - This code performs web scraping of profiles who commented on the post. It returns the **name of the user** and **profile url**.
 - [Go to File↗️](https://github.com/ozibook/Target_Audience_Analysis/blob/main/Updated_Commenters_Scraping.ipynb)

<details>
<summary>Code Explanation</summary>
<br>
- To install the packages silently
 
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/96fabda5-91cc-4177-8e64-93380a49cf1a)

 - To add the Excel file
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/0d1325d6-ac22-4a0a-9d99-ae0a7d422822)

 - Remove Duplicates
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/36bd39e5-e8bf-4b93-b2f6-023bba952be9)

 - Creating a List of Links
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/be985c85-7956-47fe-9260-3c1b716284e7)

 - For entering how many links to enter in one chunk
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/6196be46-50a3-4ad7-820e-e5d3e7d270a7)

 - Run for log in with spoof account
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/b2e9347c-4072-447d-9d9d-52aa49893a39)
   
 - Mention the chunk number to run the data extraction
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/4a73a732-07d3-4601-8730-8113c8fce108)

 - Mention how much links from start you want to comment out
![image](https://github.com/ozibook/Target_Audience_Analysis/assets/144370840/093dbc0c-288c-436c-913d-fba2a158a6d3)

</details>
 

#### 4. Modified like scraper_with_exception Code
 - This code performs the web scraping of profiles who liked the post. This is an updated code with exception handling. It returns the **name of the user** and **profile url**.
 - [Go to File↗️](https://github.com/ozibook/Target_Audience_Analysis/blob/main/modified%20like%20scraper_with_exceptionHandling.ipynb)
#### 5. TA_Analysis Code
 -  Used for profile categorization and visualization
 -  [Go to File↗️](https://github.com/ozibook/Target_Audience_Analysis/blob/main/TA_Analysis.ipynb)

# Installation Guide👨‍💻
The following libraries are required to run the code<br>
1. Install Requests<br>
```
!pip install requests --quiet
```
2. Install Selenium <br>
```
!pip install selenium --quiet
```
3. Install Web driver<br>
```
!pip install webdriver_manager --quiet
```
4. Install Pandas<br>
```
!pip install pandas --quiet
```
# FAQs❓
 * Which environment to choose?
   - It is recommended to use Jupyter Notebook.
 * More details on the topic?
   - Refer to [Go to the notion page for detail understanding of the task↗️](https://docs.google.com/document/d/1lpqrSfYIm4M5RGakFS-gzObmP9jVybTxDKrgsuAAelc/edit#heading=h.vcqhms74oo6)

# Author & Contributions
- Avinaba Ghosh
- Gautam Maurya
