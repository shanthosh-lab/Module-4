

## 🎯 Aim
To write a Python program that counts the number of words in a text file story.txt.


## 🧠 Algorithm
1. Open the file story.txt in read mode.
2. Read the entire content of the file into a variable content.
3. Split the content into individual words using the split() method.
4. Count the total number of words obtained.
5. Return this count as the output.


## 🧾 Program

def create_file(file_path, file_content):

  with open(file_path,'w') as file:
  
    file.write(file_content)

def count_words_in_file(file_path):

  with open (file_path,'r') as file:
  
    content = file.read()
    
    words = content.split()
    
    return len(words)
    


## Output


![WhatsApp Image 2025-09-01 at 16 09 22_6e815146](https://github.com/user-attachments/assets/3cf4eabc-8d6f-42be-b6f7-9833771d8739)

## Result
Thus, a Python program that counts the number of words in a text file story.txt is verified.
