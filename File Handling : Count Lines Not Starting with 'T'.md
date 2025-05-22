## File Handling in python : Read a file and count the number of words in it.
## 🎯 Aim
To write a Python program that reads a text file and counts the total number of words present in it.

## 🧠 Algorithm

1.Open the file (e.g., story.txt) in read mode.

2.Read the entire content of the file using the read() method.

3.Use the split() method to split the content into a list of words.

4.Count the number of words by finding the length of the list using len().

5.Print the total word count.

## 🧾 Program
```
def create_file(file_path,content):
    with open(file_path,'w') as file:
        file.write(content)
        
def count_words_in_file(file_path):
    with open(file_path, 'r') as file:
        content = file.read()
        words = content.split()
        return len(words)
 
```

## Output

![image](https://github.com/user-attachments/assets/65eb0dc8-3360-4d66-a7f7-59b30603769c)

## Result
THus, the program counts and displays the total number of words in the file successfully.


