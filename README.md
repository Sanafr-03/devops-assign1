# devops-assign1

#1. Creating and Renaming Files/Directories
	mkdir test_dir 
  touch example.txt 
  mv example.txt renamed_example.txt 

#2. Viewing File Contents
  cat /etc/passwd 
  head -5 /etc/passwd 
  tail -5 /etc/passwd 

#3.Searching for Patterns
  cat /etc/passwd | grep root -n

#4. Zipping and Unzipping
  zip -r test_dir.zip test_dir/
  unzip test_dir.zip -d /home/sana/unzipped_dir

#5. Downloading Files
  wget https://www.google.com

#6. Changing Permissions
  chmod 777 secure.txt

#7. Working with Environment Variables
  export MY_VAR="Hello, linux"
  echo $MY_VAR
