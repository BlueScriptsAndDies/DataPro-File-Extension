# What is .DataPro?
Its a file extension I made, its like json but worse, this has 2 parts, key and data.

# What is the key?
You dont need to use it, but can be like a password, or anything you choose!

# What is the data?
Its like the key, well it is the key but different name and stores different things, or same if you make them. This could be used as like the username, or anything you choose!

# Whats an ID?
Its the ID of the file, this can be used as a better way to find a file, the ID has 2 parts. The date, the amount of num for the key and data.
This also helps get the data and key. 

# How to install it
1. Install file, and import to project
2. Import it by using "from DataPro import *"
# How to use it
File:
ARGS: File
This is the file itself, to use it do 'var_name = File("Dir of file")'. Now you have the first part setup.

Load:
ARGS: Key, Data
This will load the file with data, to use this do 'var_name.load(key,data)'. you should see 'Successfully loaded file.name with an ID of id'

Unload:
ARGS: None
This will unload the last load, key, data and id. to do this, set a var to unload, then just use var_of_unload[0 = last load, 1 = key 2 = data 3 = id]


