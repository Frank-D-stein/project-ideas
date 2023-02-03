# Project Idea

---

## Brief Summary

    The idea for this project came to me when I was recommended a bunch of videos on YouTube all complaining about the 
    current demonitization that YouTube has been doing. After hearing this and learning that one of the main issues is
    copyrighted music I had an idea. If there is a software that any creator can run their whole video through that
    uses the same or similar algorithm that YouTube uses to find and erase any copyrighted material and warn the user
    where it took place that could be a potentially helpful tool.

---

## The Main Problem

    I think the main problem is with YouTube and its current way to treat their content creators. While reuploading 
    music videos is a legitiment reason to get demonitized the cases I've run across tend to be amoung YouTube's 
    largest creaters using incredible small portions of songs that could be easily avoided.

---

## Features

    After thinking about this issue I had an idea. If possible (Which is why I don't think this project is valid 
    especially for a school assignment) what if we could go through the audio (and down the line potentially video for
    copyrighted images) to scan and detect the material and check it using a already existing library of data. After 
    audio has been found in violation (maybe even include a likely-ness percentage in case of error) we add an option
    to remove the audio in case it is not possible, such as a video in a store with music playing for the customers. 
    This is where I am not sure if this idea would work, if we could "flip" the audio wave and play it over top of the 
    existing audio there *should* be an effect called deconstructive interference in which the audio of the music 
    would be removed. Down the line for different scenarios such as bad audio quality on copyrighted material we could 
    use a library to isolate the bad audio to remove it from the video. Prior testing is **required** to ensure that
    the audio after the program has been run is still intact because I'm not confident that their wouldnt be some audio
    issues after attempting to remove it. Maybe we could develop some way to reduce that but a video with slightly 
    worse audio in some parts is better than a video which looses the creator money. 

---

## Languages/Libraries

    I think for this project python would be a good language to start on. With tons of libraries and third party code
    there will already be some code to help with the basics such as manipulating audio and dealing with file types. 
    Using a language like C or Java might make some of the more simple problems turn into headaches. I also think there
    could be a web side to the project given the time for it. Rather than a standalone program, if it was as simple as 
    hosting a website where the customer can drag and drop the file into the browser I think it would provide a much 
    more modern user experience.

---

## Customers

   Overall if this idea is valid it would primarily be used by content creators, and given that it works and does the 
   job well, there is potentially room to capitalize on it either with a monthly subscription platform or a pay-per-use 
   scenario. Or even just to leave it online or open source for free and solicit donations.
