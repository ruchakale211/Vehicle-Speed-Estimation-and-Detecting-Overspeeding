This is a Python script that can detect the speed of multiple vehicles on multi-lane highways. It works by using Haar Cascade Classifier to identify vehicles in every nth frame and then removes unnecessary parts of the image to speed up processing. Two reference lines have been established, one for the vehicle's entry and one for its exit. When a vehicle crosses the entry line, its time is recorded, and it is tracked using centroid tracking techniques. The script records the time when the vehicle crosses the exit line. By calculating the time difference between entry and exit, the script estimates the speed of the vehicle.
This code focusses on Object Tracking and Speed Estimation of vehicles passing by a road. The camera angle is from slightly above the road, (similar to the video given)

![AbuDhabi_Traffic](https://user-images.githubusercontent.com/72432304/120893909-ad17b100-c626-11eb-92ad-4d1ff314265b.JPG)






