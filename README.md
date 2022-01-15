# backupfolder
#startfromline4

import os
import shutil

source = input("enter the source name")
destination = input("enter the destination name")

source = source + '/'
destination = destination + '/'

list_of_files = os.listdir(source)
for Files in list_of_files:
    shutil.copy = ((source + File),destination)
