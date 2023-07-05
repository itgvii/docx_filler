# docx_filler
A program for creating and filling docx forms in a browser.

Usage:
  1. In a docx document select a part of the text to ${field title}.
  2. Upload this file to server.
  3. Now you have a form, which you can fill.

Installation for Windows (local):
  1. install Python (there are Python installer in repository)
  2. launch file "installer.cmd" (it will install in your system Python interpreter the following libraries: "flask", "python-docx", "waitress".)
  3. the program is installed
  4. launch the program using "docx_filler.py" file
  5. open the link from the command promt in you browser

Manually installation (Windows, Linux):
  1. This program is just two Python files, the main file is "docx_filler.py".
  2. And two folders, which contain html pages and docx patterns (which you need to create).
  3. The Python scripts need libraries "flask", "python-docx", "waitress".
  4. You can install them via "pip install flask python-docx waitress". (first you need to install python, of course, and I also recomend you to create a virtual env)
  5. Then boot "docx_filler.py" file.
  6. By default the program is booting on the socket "127.0.0.1:5035" and it's available only on the same machine in a browser.
  7. If you want to have access from other machines, change the socket in "docx_filler.py". For example
