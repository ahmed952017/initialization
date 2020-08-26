# initialization
#learning how to use python, reading and writing on files
#read, write, append modes and + 
my_workers = open ("workers", "a")
print(my_workers.writable()) # check if the file is readable
my_workers.write("booda - tax manager")

my_workers.close()
# the new line will be added to the file
#.append: add at the end
#.write: remove and overwrite
