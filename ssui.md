# VILS (Visual Imaging Life Saver)

*Disclaimer: this project is subject to changes and is open to ideas*

## Summary

VILS is a health-monitoring and responsive system that detects and intervenes in life-threatening situations. Using camera, audio, and application-based input, VILS identifies the user’s current state and visual input, such as spikes in heart rate and universal distress hand signals. The application plans to communicate across different platforms, such as embedded microcontrollers, smartwatches, and a desktop application.

## Problem

Once people decide to venture into the world in isolation, such as going to college or moving to a new city, people often find themselves living alone. The Census Bureau of the United States released that 28% of households were recorded as “single-person.” Without the supervision of another person, this can lead to unfortunate and fatal occurrences, such as choking with nobody to perform the Heimlich maneuver.

## Features

VILS plans to resolve this problem by using an AI-powered engine to power a system that watches over the user, like a guardian angel. Unlike companies that only want to steal personal data, VILS only stores information pertinent to the survival of the user.
By being trained on sample data, VILS is built on a convolutional neural network (CNN) to efficiently analyze and perform classification on given input images/frames. The CNN’s output will detect (currently) hand signals, such as the distress hand signal. 

## Language/Tools

- Python 
    - OpenCV - Process the visual information
    - Torch/TensorFlow - Engineer the neural network for image classification (and possible speech recognition)
- HTML/CSS/JS - Frontend
    - Electron - Apply the stack as a desktop application
    - Flask - Embed the Python application/model into the application
- Swift - watchOS for smartwatch data tracking

## Target Audience

This application will appeal to those who believe in “better safe than sorry.” Ideal users would be people who commonly live alone, such as college students or elderly people. The system plans to be augmented and developed with more ways to help and identify negative impacts, such as physical (factory workers being injured) and mental (stress readings from an IoT device, like a smartwatch). Overall, this product aims to cultivate AI in an area that is oftentimes overlooked with current use cases.

