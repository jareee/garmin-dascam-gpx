# garmin-dash-camera-gpx


This Pytho script processes video files from a specified folder to generate a GPX file containing GPS data.
The GPX file will be named "Output-<folder_name>.gpx" and will be placed inside the folder.

To run the script, use the following command:
python script_name.py "path_to_video_folder"

Replace script_name.py with the name of this script.
Provide the path to the video folder in quotes if it contains spaces or special characters.

Sometiimes Garmin Dash Cameras GPS data is saved embeded in video files with two parallel tracks, track 0 and track 3. 
For not having looped gps data in gpx file, data is processed from the point when Track ID is 3. 

Any updates and changes to code are welcome. 
