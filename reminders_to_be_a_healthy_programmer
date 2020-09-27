#Progrm Name:Timer to make you  a healthy programmer
from pygame import mixer
import datetime
import time
d=datetime.datetime.now()



def music1(file):
    mixer.init()
    mixer.music.load(file)
    mixer.music.play(5765)
    while (1):
        string = input("Enter 'okay' to stop the music.")
        if string == "okay":
            mixer.music.stop()
            break
        else:
            continue


def gettime1():
    return datetime.datetime.now()


water=time.time()
eyes=time.time()
physical=time.time()
watertime=30*60
physicaltime=60*60
eyestime=45*60



while(1):
    if time.time()-water>=watertime:
        print("-----------------------------------------------------------------------------------")
        print("------------------------------------Drink Water!------------------------------------")
        print("-----------------------------------------------------------------------------------")
        music1("water.mp3")

        water=time.time()
        with open("water.txt","a") as f11:
            f11.write(str(gettime1()))
            f11.write("\n")

    if time.time()-eyes>=eyestime:
        print("-----------------------------------------------------------------------------------")
        print("------------------------------------Give Rest to Your Eyes------------------------------------")
        print("-----------------------------------------------------------------------------------")
        music1("eyes.mp3")
        eyes=time.time()
        with open("eyes.txt","a") as f22:
            f22.write(str(gettime1()))
            f22.write("\n")
    if time.time()-physical>=physicaltime:

        music1("physical.mp3")
        print("-----------------------------------------------------------------------------------")
        print("------------------------------------Its Exercise Time!---------------------------------")
        print("-----------------------------------------------------------------------------------")
        physical = time.time()
        with open("physical.txt","a") as f33:
            f33.write(str(gettime1()))
            f33.write("\n")
