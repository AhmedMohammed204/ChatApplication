<H1> Tables </H1>
Here's the documentation of project tables

<details>
<summary>Diagram</summary>

<img src="https://github.com/AhmedMohammed204/ChatApplication/assets/149516109/3ec67fbc-a4ad-455f-80f6-2479d57a66a5" />

</details>

### Users Table
#### Columns:
- UserID
  > primary key

- Username
  > Unique
  > 
  > Contain check constraint which is (charindex(' ',[Username])=(0)) to make sure that username doesn't contain spaces

- Password
  > Contain check constraint which is (len([Password])>=(8)) to make sure that password's length is more than 8 characters
  

- Name
- Photo
- Bio
- Last Seen
- IsActive
  > For soft deleting

<details>
  
<summary> Table diagram </summary>


![image](https://github.com/AhmedMohammed204/ChatApplication/assets/149516109/43dde30e-2088-4655-8793-1b69dc48022b)

</details>


  
