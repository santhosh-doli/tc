# About Compare Preferences KNIME Workflow
A visually engaging desktop application on KNIME platform to generate a report comparing Preference XML files.
Helpful when the entries are jumbled and have lot of entries / differences making text based compare difficult.
Easy to Read excel comparision results showing what's missing, modified and extra

![Prefernces Comparator Workflow](./image_file.jpg)

# How to use
1. Download, install and run the KNIME application (https://www.knime.com/).
2. Download the KNIME workflow (.knwf file extension) from this repo.
3. Import the KNIME workflow into the application. Use File -> Import... ( See below 'Help to find Import option' if you can't find ).
4. The workflow gets imported. Follow the instructions to provide input and execute.
5. Results Excel opens up automatically.

# Help to find Import option
By default KNIME opens up in the 'Modern UI' and the current version (5.3.1) does not support import/export options.
Switch to the 'Classic UI' by using the 'Menu' button at the Top-Right Corner of the application.

# Limitations
Only Preference Name and Values are compared. Not other attributes like Type, Array.
