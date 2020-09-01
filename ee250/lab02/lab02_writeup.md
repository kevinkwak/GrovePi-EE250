4.1
git clone git@github.com:my-name/my-imaginary-repo.git
touch my_second_file.py
git add my_second_file.py
git commit -m "Added second file"
git push

4.2
I did development on my VM while SSH'ed on to my RPi. I used Vim as my text editor as it is easy to use in the terminal of my VM and was easy to install on my RPi. I pushed/pulled changes within my RPi using SSH.

4.3
There is a small delay of 0.06 s (must be greater than 50ms) in the ultrasonicRead() function due to the firmware. The RPi uses I2C serial when trying to communicate with the microcontroller to read the ultrasonic ranger output using the "grovepi" library.
