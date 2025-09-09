# Faceit overlay for OBS 
## Overlay is displayed when winning or losing
#1. Download Pyhton 
# 2. After download create Client side Faceit API key https://developers.faceit.com/
![1](https://i.pinimg.com/736x/ae/f8/d8/aef8d8ba80c641df5f8c8fc0a166fa69.jpg)
# 3. Then open the index.html and paste the API key and your nickname.
![2](https://i.pinimg.com/736x/80/2e/10/802e10109ed7814c5119283a8b6c14e5.jpg)
# 4. Create a shortcut in the index.html folder in the field we enter this command 
```cmd /c "cd /d Path to folder && python -m http.server 8000 --cgi"```
# 5. After launching cmd, open OBS, create a browser and insert the URL address http://localhost:8000/
# 6. You can change background 

![2](https://i.pinimg.com/736x/0e/dd/da/0edddafbd2ee8e4df0b96891d8bb9526.jpg)

### There is a nuance: each time you start the flow, you need to insert the link again. Make sure that the request appears in cmd. Then start the flow.
### An example of what it looks like
![3](https://i.pinimg.com/736x/88/0f/d9/880fd93b93c16b05ce1a5c55df216690.jpg)
