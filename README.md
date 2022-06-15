# Music-Player

we will create a music player in which we can play the music, pause, stop or resume the music.
We are creating a project using the tkinter and pygame module. Using the Tkinter library we are creating a GUI for the music player.
Project Prerequisite

This project requires good knowledge of python and the Tkinter library. Tkinter is the python binding to the Tk toolkit which is used across many programming languages for building Graphical user interface which is GUI. To work on this project basic understanding of the pygame module is also required.

Steps to Build a Python MP3 Music Player

Below are the steps to create Python MP3 Player:

    Import modules
    Initializing root window
    Create a function for adding and playing music
    Make icon and logo
    Create music player buttons

Importing Modules

    import mixer – It will import pygame. Use for manipulation of the song tracks.
    Tkinter module – Tkinter is the standard interface in python for creating a GUI that is Graphical User Interface.
    tkinter import * – import everything from the module.
    import os – This is the functional module in order to get the data from your computer.

Initializing root window

    root tk() – Initializing the main window
    root.title() – for setting the title of the music player which will display on the top of the window.
    root.configure() – for setting background color.
    mixer.init() – Initializing the pygame mixer module. window
    For displaying directly to the GUI here we use string variable.

Create music player functions to player mp3

    Add music() – Function for adding the music from the directory.
    Here we have created an if loop in which we have given the path of the directory, so we can open any folder from our directory where our music files are saved.
    After choosing the music file from the directory , select the particular song and play the music using play music function.

Make icon and logo

    Icon image() – for adding an image to the icon.
    Photoimage – this method returns the image.

Create music player buttons

    Buttons are created using the tkinter module.
    Here we have created a play, pause, stop and resume button.
    Root – We want the buttons in our main window so we are calling root here.
    Text – Specified text will display on the button.
    Command – Command function which will be called when the button is clicked.
    We are calling config for setting font, font color, background color, border width and padding.
    place() – For placing the button at the proper position.
    scroll – Here we are creating a frame at the right side of the window which will show our playlist. And the scrollbar controls the up and down moment of the listbox.
    
