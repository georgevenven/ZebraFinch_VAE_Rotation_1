# ZebraFinch_VAE_Rotation_1

## My rotation 1 work:

The code does not work out of the box because many of the paths were hard coded / contained an esoteric file structure. So to get this working, you must set up your own file structure etc etc find out how you want to organize the data flow. Feel free to dm / email me if you need assistance. 


## This is an abstract, 30k feet view of how the process works:
1. Get all song files you wish to analyze, and create a folder with each day in a sperate folder
2. Generate a rhytmicity vs time plot of each file, and store them in the /segments folder (make sure the og song files still exist in their own folder)
3. Put the rythmicity vs time plots through the VAE, the vae.ipynb should generate a good_file.txt file (or something with a similar name)
4. Then, use the song_extractor.ipynb to generate the segments needed for the VAE
5. Retrain a new VAE with the new segments folders
6. You can now create UMAPs or whatever you wish to do


## Code To-Do and Improvements:
1.  Write a To-Do List


