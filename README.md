# Real-Time-Video-Analysis

### Problem Statement
Your assignment is to develop a video platform similar to YouTube that allows
users to watch videos. Your task is to implement the following features:
1. Sign up/Login functionality
2. Capture user events such as video watch time and the number of times
a user has watched a particular video etc.
3. Provide analytics for each user and video analytics like average
duration of video watched per user, most watched video, average user
session vs duration of videos watched during that session etc.

### Results
Attached below is the admin dashboard, where analyst can process the data fetched from the user events captured.
<!-- ![image](https://user-images.githubusercontent.com/81441938/226687698-34968270-2407-46d6-a102-30c2c1bfcf98.png) -->
<img src="https://user-images.githubusercontent.com/81441938/226687698-34968270-2407-46d6-a102-30c2c1bfcf98.png" width="700">

### To run the project
execute command: 
```python manage.py runserver```

### Run-Through
- Go to http://127.0.0.1:8000/ [The home page]
- Click on ```login to continue to player``` button
- Choose your google account to login <br>
<!-- ![image](https://user-images.githubusercontent.com/81441938/226689494-329b73be-61a7-4a10-acb7-a44ceb45b275.png) -->
<img src="https://user-images.githubusercontent.com/81441938/226689494-329b73be-61a7-4a10-acb7-a44ceb45b275.png" width="400">

- Further you will see an interface like this: <br>
<!-- ![image](https://user-images.githubusercontent.com/81441938/226689648-cf5c9fad-29eb-4c61-a590-175443627d57.png) -->
<img src="https://user-images.githubusercontent.com/81441938/226689648-cf5c9fad-29eb-4c61-a590-175443627d57.png" width="400">

- You can play the video or choose a different video by clicking below hyperlinked video titles.
- This data will be captured and will be reflected in the ```http://127.0.0.1:8000/player/analysis``` url. [whose screenshot attached in Results section]
- You can logout from the player by simply clicking on ```logout``` button, which will in turn end your session.
- You can visit Django Admin page by going to ```http://127.0.0.1:8000/admin/```, use the ```username: sahil``` and ```password: 12345678```
- On entering you can see the admin site
<!-- ![image](https://user-images.githubusercontent.com/81441938/226691674-b03e2b86-1b3b-4e62-9ef3-3eafe397bb5e.png) -->
<img src="https://user-images.githubusercontent.com/81441938/226691674-b03e2b86-1b3b-4e62-9ef3-3eafe397bb5e.png" width="400">

- Can Find the 3 data tables under player App
1. User events	
2. User sessions	
3. Videos
<!-- ![image](https://user-images.githubusercontent.com/81441938/226692392-fc153f2e-a6f4-4412-874f-0c42d6ef44f2.png) -->
<img src="https://user-images.githubusercontent.com/81441938/226692392-fc153f2e-a6f4-4412-874f-0c42d6ef44f2.png" width="400">

- You can upload new video also there:
<!-- ![image](https://user-images.githubusercontent.com/81441938/226692651-4d59c001-ac2f-4251-9f66-286fee878bc6.png) -->
<img src="https://user-images.githubusercontent.com/81441938/226692651-4d59c001-ac2f-4251-9f66-286fee878bc6.png" width="700">

### Code
- Most of the backend code is written in the file [player/views.py](https://github.com/SahilKhan101/Real-Time-Video-Analysis/blob/main/player/views.py)
- JavaScript code for capturing the event and sending the data to backend API in [player/templates/player.html](https://github.com/SahilKhan101/Real-Time-Video-Analysis/blob/main/player/templates/player.html)

> ## The End


