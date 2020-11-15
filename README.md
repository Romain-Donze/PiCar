# PiCar

PiCar is a python app to run the PiRacer-pro from waveshare based on Raspberry-pi 4

If you find an issue, please [let us know](../..//issues)!

## Setup

Follow the steps below to download PiCar directly onto your pi.

On the Raspberry Pi, run these commands

    # Install libraries
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get install build-essential python3 python3-dev python3-pip python3-virtualenv python3-numpy python3-picamera 
    sudo apt-get install python3-pandas python3-rpi.gpio i2c-tools avahi-utils joystick libopenjp2-7-dev libtiff5-dev gfortran 
    sudo apt-get install libatlas-base-dev libopenblas-dev libhdf5-serial-dev git ntp
    sudo apt-get install libilmbase-dev libopenexr-dev libgstreamer1.0-dev libjasper-dev libwebp-dev 
    sudo apt-get install libatlas-base-dev libavcodec-dev libavformat-dev libswscale-dev libqtgui4 libqt4-test
    
    # Download the app from github
    cd ~
    git clone https://github.com/Romain-Donze/PiCar.git
    
    # Run the app
    python3 ./PiCar/manage.py
