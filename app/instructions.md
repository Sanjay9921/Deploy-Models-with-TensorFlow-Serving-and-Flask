### INSTRUCTIONS ###

1. To run the app: $python3 app.py
2. Right-Click on the local addr "127.." -> Open Link in new tab

### Few cmds used ###

$sudo docker ps

$sudo docker run -p 8582:8581 --name=pets -v "/home/rhyme/Desktop/app/pets/:/models/pets/1" -e MODEL_NAME=pets tensorflow/serving

