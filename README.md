# Automatic File Sorter (Python)

## **Background**

In this digital age, we always download files from internet/application to our computer. The problem is, not everyone has the time to sort files every day. I mean, just look at my personal download directory:

<br>
<p align="center">
  <kbd><img src="assets/photo1.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>

My download folder has 45 files. It used to be so much more (over 1000!), and honestly I've gotten tired of sorting it manually. I mean, who doesn't, right?

<br>

To tackle this, I look into my old friend Google, and to my surprise, you can actually use Python. So, I decided that it was time to sort the files into each folder by utilizing Python.

<br>

## **Preparation**

For sorting files in Python, we are going to need several modules, namely:
* **os** module: **os** is a module in Python that enables us to interact with the operating system. Essentially, we can create files, create directories, and even manage the files and directories itself. Some examples (including what are we going to use) are:
  ** os.getcwd(): Handle current directory.
  ** os.mkdir(): Create directory.
  ** os.rename(): Rename files (can also be used to place file into their respective folders.

* **collections** module: **collections** is a module in Python that helps us organize and work with your data in different ways, such as counting items or make a list where you can easily add or remove items. Examples are:
  ** Counter(): Count how many values a value appear.
  ** OrderDict(): Remembers the order of inserted value.
  ** DefaultDict(): Provide some default values for the key.

<br>

## **Code**

First, the modules needed was imported from the library (**os** and **collections**). After that, files were categorized by their type.

<br>
<p align="center">
  <kbd><img src="assets/photo2.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>

Files that has been categorized then double checked to make sure the categorization went smoothly.

<br>
<p align="center">
  <kbd><img src="assets/photo3.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>

Next step is to create the files based on category that was created before, to divide files to folders based on file type. 

<br>
<p align="center">
  <kbd><img src="assets/photo4.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>

Finally, creating loop function to move the files based on their type. To make sure the operation went smoothly, call out print function (move 'file' to 'folder') so that we can see where the file was moved into. Then, end it with a text: Your file has been sorted! 

<br>
<p align="center">
  <kbd><img src="assets/photo5.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>
<p align="center">
  <kbd><img src="assets/photo6.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>

Let's see the final result.

<br>
<p align="center">
  <kbd><img src="assets/photo7.jpeg" width=800px> </kbd> <br>
</p>
<br>
<br>

Et voilà, much cleaner than before. We have successfully made a mini file organizer!
